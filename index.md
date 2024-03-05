# my header 1

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

``` terraform
resource "aws_instance" "app_server" {
  ami           = "ami-08d70e59c07c61a3a"
  instance_type = "t2.micro"

  tags = {
    Name = "ExampleAppServerInstance"
  }
}
```
