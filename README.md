# DO-Product-Card

Testing NPM package deployment

### Fausto Zaruma

## Example

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'do-product-card'
```

```
                <ProductCard
                    product={product}
                    initialValues={{
                        count: 4,
                        // maxCount: 10,
                    }}
                >
                    {({ reset, increaseBy, isMaxCountReached, count }) => (
                        <>
                            <ProductImage />
                            <ProductTitle />
                            <ProductButtons />
                        </>
                    )}
                </ProductCard>
```
