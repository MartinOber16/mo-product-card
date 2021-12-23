# MO-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Martin Obermeier

## Ejemplo
```
import {} from 'mo-product-card'
```

```
<ProductCard 
    key={ product.id }
    product={ product }
    initialValues={{
        count: 4,
        // maxCount: 10
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
            <> 
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```