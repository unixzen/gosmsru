# gosmsru
Simple implementation of sending sms by sms.ru

### Configuration

Config file gosmsru.yaml must located at the same folder with gosmsru binary file.
At config file gosmsru.yaml need set two parameters: 

`api_id` - API id which you can find at personal area of sms.ru

`to` - phone numbers separated by commas to which you want to send a message

### Build

At directory with gosmsru.go 

```
go build gosmsru.go
```

### Usage

```
./gosmsru -msg "hello world"
```


