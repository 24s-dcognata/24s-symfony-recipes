# 24S Symfony Recipes



## Getting started

### Use 24S Symfony Recipes on your project

Add new symfony flex endpoint in your `composer.json`

```json
{
    "extra": {
        "symfony": {
            "endpoint": [
                "https://gitlab.com/24s-dcognata/24s-symfony-recipes/contents/index.json",
                "flex://defaults"
            ]
        }
    }
}
```