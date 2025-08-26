## Create a bucket
```
aws s3 mb s3://encrypt-client-fun-hp-63423
```

### Run our our SDK ruby script
```
bundle exec ruby encrypt.rb
```

# Cleanup 
```
aws s3 rm s3://encrypt-client-fun-hp-63423/hello.txt
aws s3 rb s3://encrypt-client-fun-hp-63423
``