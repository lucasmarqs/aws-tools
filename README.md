AWS Tools
=========

My personal scripts I daily use to make some stuffs on AWS

Index
-----

### [epifes](./epifes)

Returns the Private IP of the EC2 instance for a given ECS service name and its cluster.

```sh
./epifes myService production
#=> 10.50.12.99
```

### [ssmget](./ssmget)

Get parameters on SSM for a given list of names.

```sh
./ssmget name_1
#[
#    {
#        "Name": "name_1",
#        "Value": "val_1"
#    }
#]
```

### [ssmput](./ssmput)

Put a parameter on SSM. See file for more reference.

```sh
./ssmput name_2 --value val_2 --type String
#{
#    "Version": 1
#}
```

License
-------
This project is licensed under [GLWTPL](https://github.com/me-shaon/GLWTPL/blob/master/LICENSE)
