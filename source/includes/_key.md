# Key

Get information about the API key you are using

## Get permissions

```python
client.get_key()
```

```javascript
client.getKey(function (err, ticker) {
  console.log("key err", err);
  console.log("key", ticker);
});
```

```php
<?php
client->getKey();
?>
```

```ruby
client.get_key()
```

```ruby
# Hashie::Mash Object
key.permissions.each do |permission|
permission
end
```

```python
# Dict Object (Array)
[
  "get-account",
  "create-buy",
  "create-sell",
  "cancel-order"
]
```

```javascript
// JSON Object (Array)
[
  "get-account",
  "create-buy",
  "create-sell",
  "cancel-order"
]
```

```php
<?php
// Array Object
[
  "get-account",
  "create-buy",
  "create-sell",
  "cancel-order"
]
?>
```

Get all the permissions associated with this key

### HTTP Request

`GET /v1/key`


