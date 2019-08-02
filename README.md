# Chain

Tool for building multi-image projects using cekit  

---
**NOTE**
This is a bag of scripts used to automate the image build process of [AMQ Streams](https://github.com/jboss-container-images/amqstreams-1-openshift-image). This project is a WIP. It is not ready for use.

TODO:
* Fix for current set of AMQ Streams images
* Add proper install procedure
* Add proper configuration procedure
* Create tests
* Genericise for flexibility
---

# Getting Started

Download dependencies
`pip3 install -r requirements.txt`

Displays a list of build options
`./chain.py --help`

Builds all the images
`./chain.py build`
