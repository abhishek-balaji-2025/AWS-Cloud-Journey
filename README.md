# AWS-Cloud-Journey
A collection of my journey learning and working with Amazon Web Services (AWS). This repository will include scripts, tutorials, architectural designs, and lessons learned as I dive deeper into the cloud computing world.

# yaml syntax required to operate cloudformation

AWSTemplateFormatVersion: '2010-09-09'

Description: A short description of the template.

Parameters:
  ParameterName:
    Type: String
    Default: default-value
    Description: Description of the parameter

Mappings:
  MappingName:
    Key:
      Name: Value

Resources:
  LogicalResourceName:
    Type: AWS::Service::ResourceType
    Properties:
      PropertyKey: PropertyValue

Outputs:
  OutputName:
    Description: Description of the output
    Value: !Ref LogicalResourceName
