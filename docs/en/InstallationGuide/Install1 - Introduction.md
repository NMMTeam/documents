# Introduction

## Document Overview

This Installation Guide includes PSS®ODMS installation, licensing and
database configuration instructions and is designed to supplement the
PSS®ODMS User Manual and other standard product documentation.

## About PSS®ODMS

PSS®ODMS is a Siemens PTI commercial software product that leverages
proven technology and is designed to run on Microsoft Windows. PSS®ODMS
has an open architecture that includes public .NET and Python APIs to
facilitate automation and integration with external systems. Commercial
database software, Microsoft .NET Framework and Python for Windows are
separately installed prerequisites.

## Physical Deployment

A traditional PSS®ODMS deployment involves a central database server
with multiple PC workstations, each with PSS®ODMS and its prerequisite
software installed. Each running PSS®ODMS application instance connects
to the database server via LAN connection. As a general rule, the
workstations and database server should be on the same subnet.
Workstation and server hardware specifications and local network
bandwidth are important performance considerations.

A more modern and efficient deployment approach involves installing
PSS®ODMS on a dedicated application server VM running Windows Server
2016 or higher. SQL Server may be installed on the same VM or on a
different VM within the same virtual environment. Users connect to the
application server via Remote Desktop Services (RDS) and run the
PSS®ODMS application in the server desktop environment. The number of
concurrent PSS®ODMS users is restricted by software licensing. The
specifications of both the virtual application server and its physical
host are important performance and scalability considerations. Multiple
environments (e.g. Production, Test, and Backup) are easily supported.

A PSS®ODMS deployment with State Estimator-based network analysis
functionality additionally requires OPCsync, an OPC client service that
interfaces with an exteneral OPC server to retrieve real-time or
historical measurement values. OPC DA, OPC HDA and OPC UA protocols are
supported.

For a lightweight, single-user deployment, PSS®ODMS can be installed on
a Windows 10 machine along with SQL Server Express Edition. This
approach can also be used to provide additional flexibility within a
multi-user deployment.

## PSS®ODMS Support

For PSS®ODMS installation or other support, contact Siemens PTI Software
Support:

Web: www.usa.siemens.com/odms-support

Phone: +1 518-395-5075
