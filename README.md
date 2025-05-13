Resources:
  SimpleEC2Instance:
   Type: "AWS::EC2::Instance"
   Properties:
   Instance Type: t3.micro
   InstanceID: ami-0f88e80871fd81e91
   Tags:
   -key: Name
   Value: MySimpleInstance
