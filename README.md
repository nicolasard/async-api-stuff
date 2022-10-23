## AsyncAPI Nico examples

### Code Generation tools (.yaml first) 

To generate the code from the AsyncApi def. I'm using the plugin from https://github.com/corunet/scs-multiapi-plugin. For some reason the plugin can't get the https://github.com/corunet/scs-multiapi-plugin/tree/main/multiapi-engine package from the Maven repositories so I had to install it my local repository.

```
> git clone https://github.com/corunet/scs-multiapi-plugin.git
> cd ./scs-multiapi-plugin/multiapi-engine
> mvn clean install -DskipTests
```

### Example 1
