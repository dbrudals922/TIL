## vue
비동기식 = 순차적으로 동작?<br>
동기식 = 같이 함.<br>

vue<br>
```javascript
const errRes = await axios.put('api/error', this.error)
```
<br><br>
springboot<br>
```java
@RequestMapping(value = "/error", method = ReqeustMethod.PUT, consumers = MediaType.APPLICATION_JSON_VALUE)
  public void updateError(@requestBody ErrorConfiguration error){
    this.flowSettings.setError(error);
  }
```
