# SoapUI-Robotframework
Its all about Soap UI integration with Robot framework
Below is the .robot file properties
*** Settings ***
Library           E:\\SoapRobot\\SoapUILibrary.py
SoapUI Project  C:\\Users\\GSIS 2.7 - CIM.20-soapui-project.xml
SoapUI Set Project Property  ServiceEndpoint=http://hwrllb01/GSIS_APIService/cim_2_0/CIMService.svc # set a single property |
SoapUI Set Project Property  Username=bk  # set a single property |
SoapUI Set TestCase Property  Password=****  # set a single property |

