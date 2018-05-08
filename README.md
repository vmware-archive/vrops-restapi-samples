

# vrops-restapi-samples

## Overview

vRealize Operations REST API provides programmatic access for developers and administrators who would like to automate routine tasks or integrate with other solutions.  The APIs are documented fully on the vRealize Operations appliance and an [API Guide is available here](https://https://docs.vmware.com/en/vRealize-Operations-Manager/6.7/vrealize-operations-manager-67-api-guide.pdf).

The easiest way to get started is using the Postman Client to try out the APIs.  Postman allows you to export code samples in many scripting and programming languages, so the purpose of this repository is to provide examples in a generic format using Postman.

Postman allows you to export code samples in many scripting and programming languages, so the purpose of this repository is to provide examples in a generic format using Postman.

### Prerequisites

* [Postman Client](https://www.getpostman.com/)
* [vRealize Operations 6.x](https://my.vmware.com/en/web/vmware/evalcenter?p=vrops-eval)

### Using the Samples

1. Download the Postman collection file from the Samples folder
2. Import the collection file into Postman
3. Define your vRealize Operations environment.  At a minimum the environment needs to contain:

  * user: *your vRealize Operations user account*
  * pass: *your vRealize Operations user password*
  * vrops: *IP of your vRealize Operations node*

For example:

```
user : admin
pass : VMware1!
vrops : 192.168.1.50
```

Additional environment vars will be created by some of the API samples.  There is usually no need to edit those.


## Contributing

The vrops-restapi-samples project team welcomes contributions from the community. If you wish to contribute code and you have not
signed our contributor license agreement (CLA), our bot will update the issue when you open a Pull Request. For any
questions about the CLA process, please refer to our [FAQ](https://cla.vmware.com/faq). For more detailed information,
refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Refer to [LICENSE.txt](LICENSE.txt)
