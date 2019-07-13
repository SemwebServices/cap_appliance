## CAP Appliance

Welcome to the Documentation site for the "CAP Appliance". CAP Appliance is a pre-configured
build of CAP tools designed to work together so organisations wishing to draft, publish,
consume and aggregate CAP Alerts can do so in just a few clicks.

### CAP Appliance on AWS

CAP Applicance is made available as an AMI on Amazon Marketplace. All the tools composing the
CAP Applicance are open source licensed, and the distribution is made available without support
or warranty. A small fee is made for using the image, and all funds generated will go back into
the maintenance and development of the toolkit.

Although no formal SLA or support is available, community support is available and users are welcome to
submit issues to [The CAP Appliance Issue Tracker](https://github.com/SemwebServices/cap_appliance/issues)

### Using the CAP Appliance

#### Considerations before you launch a new CAP Appliance

This image is intended as a quick-start for developers and organisations wishing to trial the CAP Collator and Feed aggregation systems. It is intended for
testing and development use. The components all support cluster deployment over multiple availability zones. If you wish to run production emergency alerting
systems you are strongly encouraged to engage the CAP community for support in planning and implementing your system. This system is not intended for
production use in life critial situations, and the tooling is not yet been certified for that use.

These instructions are provided for a bare bones install. You may want to think about fronting these applications with an AWS Elastic Load Balancer, https termination
and a proper DNS setup. Setting up these things before proceeding will save you headaches later on. That said, you can launch as many copies and versions of the image
as you like, so setting up a disposable test system just to try the system is entirely fine.

#### navigate to the CAP Appliance on AWS Marketplace

#### Launch a new instance (We suggest a M5.large as a minimum)

#### Visit http://your-instance-ip/CAPCollator/setup to initialise the CAP Collator

#### Visit http://your-instance-ip/feedFacade/setup to initialise and setup the FeedFacade app

#### Load the default subscriptions

#### Set up a webhook

#### Enable one or more feeds

#### Use the system
