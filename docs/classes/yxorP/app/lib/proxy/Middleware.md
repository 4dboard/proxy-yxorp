***

# middleware





* Full name: `\yxorP\lib\proxy\middleware`
* This class is marked as **final** and can't be subclassed
* This class is a **Final class**




## Methods


### cookies



```php
public static cookies(): mixed
```



* This method is **static**.







***

### httpErrors



```php
public static httpErrors(): mixed
```



* This method is **static**.







***

### history



```php
public static history(mixed& $container): mixed
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$container` | **mixed** |  |




***

### tap



```php
public static tap(callable $before = null, callable $after = null): mixed
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$before` | **callable** |  |
| `$after` | **callable** |  |




***

### redirect



```php
public static redirect(): mixed
```



* This method is **static**.







***

### retry



```php
public static retry(callable $decider, callable $delay = null): mixed
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$decider` | **callable** |  |
| `$delay` | **callable** |  |




***

### prepareBody



```php
public static prepareBody(): mixed
```



* This method is **static**.







***

### mapRequest



```php
public static mapRequest(callable $fn): mixed
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fn` | **callable** |  |




***

### mapResponse



```php
public static mapResponse(callable $fn): mixed
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fn` | **callable** |  |




***


***

