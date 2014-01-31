#A Disruptive Collision

At the best of times, the practice of information security is defined by disruption. We need to respond to business and technology innovations -- not only from those we defend, but also from their attackers. Security is never really in control of our own destiny -- we are tasked with managing the risks of decisions made by others, in the face of entire industries (and economies) dedicated to discovering new ways of stealing or hurting them and us. We are reactive because those we protect and those who attack are never fully predictable -- not because of an inherent failing of security.

But the better we predict these disruptions, and the better we prepare our response, the more effective we are.

As analysts, we at Securosis focus most of our research on the here and now -- on how best to tackle the security challenges faced by CISOs and security professionals when they show up to work in the morning. Occasionally as part of this research we note trends with the potential to dramatically affect the security industry and our profession.

We currently see what appears to be the largest combination (collision) of disruptive forces since the initial adoption of the Internet -- with implications for security far *beyond* our first tentative steps onto the global network. Additionally, we have identified six key trends which are currently altering the practice of security. This combination of external and internal change is fundamentally transforming the practice of security.

This paper starts with a description of the disruptive forces and the native security trends, but its real objective is to lay out their long-term implications for the practice of security -- and how we expect security to evolve for security professionals, security vendors, and cloud and other infrastructure providers. Through the report we will back up our analysis with real-world examples that show this transformation isn't a vague possibility in a distant future, but is already well under way.

But although these changes are inevitable, they are far from evenly distributed. As you will see, this provides plenty of time and incentive for professionals and organizations to prepare.

##Two Disruptive Innovations

Clayton Christensen first [coined the term "disruptive technology" in 1995](http://en.wikipedia.org/wiki/Disruptive_innovation) (he later changed the term to "disruptive innovation") to describe new business and technology practices that fundamentally alter, and eventually supersede, existing ones. Innovation always causes change, but *disruptive innovation mandates change*. Innovation creates new opportunities and disrupts old ones.

The technology world is experiencing a combination of two disruptive innovations simultaneously colliding and reinforcing each other. *Cloud computing* alters the consumption and delivery models for technology at both economic and technical levels. Advances in *mobile technology* are changing our access and consumption models, and reinforcing demand for the cloud -- particularly at scale.

###Cloud Computing

Cloud computing is a radically different technology model -- it is *not* simply the latest flavor of outsourcing. It uses a combination of *abstraction* and *automation* to achieve previously impossible levels of efficiency and elasticity. This, in turn, creates new business models and alters the economics of technology delivery and consumption.

Sometimes this means building your own cloud in your own datacenter; other times it means renting infrastructure, platforms, and applications from public providers over the Internet. Public cloud services eliminate most capital expenses, shifting them to on-demand operational costs instead. Private clouds allow more *efficient* use of capital, may reduce operational costs, and make technology more responsive to internal needs.

Cloud computing fundamentally disrupts traditional infrastructure because it is more responsive, more efficient, and potentially more resilient and cost effective than our old ways of doing things. These are the same drivers that pushed us toward application service providers and virtualization. Public cloud computing is even more disruptive because it enables organizations to consume only what they need without maintaining overhead, while still rapidly responding to changing needs at effectively infinite scale (assuming an adequate checkbook).

Every major enterprise we talk with today uses cloud services, and even some of the most sensitive industries, such as financial services, are exploring more extensive use of public cloud computing. We see no technical, economic, or even regulatory issues slowing this shift.

Many security professionals focus on the multitenancy risks introduced by cloud, but *abstraction* and *automation* are more significant than shared infrastructure or services. Many security controls today rely on knowing and managing the physical resources that underpin our technology services. Abstraction breaks this model by virtualizing resources (including entire applications) into resource pools managed over the network. We give up physical control and shift management functions to standard network interfaces, creating a new *management plane*. This separation and remote management challenge or destroy traditional security controls.

Abstraction is central to virtualization, and we are at least nominally familiar with its issues. But this kind of automation is specific to the cloud, and adds an orchestration layer to efficiently utilize resource pools. It enables extreme agility, such as servers that exist only for hour or minutes -- automatically provisioned, configured, and destroyed without human interaction. Application developers can check in a piece of code, which then runs through a dozen automated checks and is pushed into production on a self-configuring platform that scales to meet demand. Security that relies on controlling the rate of change, or that mandates human checks, simply cannot keep up.

Virtualization is the core enabling technology of abstraction, and Application Programming Interfaces (APIs) are the core enabler of automation. The elasticity and agility they together provide enable new operational models such as *DevOps*, which consolidate historically segregated management functions to improve efficiency and responsiveness. Combined with greater reliance on public cloud computing, the Internet itself becomes the interconnected platform for our applications and workloads.

>Defining DevOps
>
>DevOps is [an IT model that blurs the lines between development and IT operations.](http://en.m.wikipedia.org/wiki/Devops) Developers play a stronger role in managing their own infrastructure through heavy use of programming and automation. Since cloud enables management of infrastructure using APIs, it is a major enabler of DevOps. While it is incredibly agile and powerful, lacking proper governance and policies it can also be disastrous since it condenses many of the usual application development and operations check points.

These changes aren't bad or inherently risky, but they require new approaches. In some cases they offer opportunities to wipe out classic security issues, enabling resources to be shifted to new priorities.

Between business benefits and current adoption rates, we expect public cloud computing to become the dominant technology model over the next ten to fifteen years. As we make this transition *it is the technology that creates clouds, rather than the increased use of shared infrastructure, that really matters for security*.

###Mobility

Walk down the street, pull your eyes from your phone, and look around you. In less than a decade we moved from most technology services being accessed from desktop and laptop computers to access from mobile devices with near-ubiquitous wireless high-speed networks. It is hard to fully grasp how rapidly this shift has occurred, and its implications.

Workers don't wait to be issued a corporate phone -- they walk in the door with a computer in their pocket more powerful that what was on the desks five years ago. They expect to access email and other corporate services from wherever they are, on whatever device they have. Some organizations are able to limit this somewhat, but we see generations of workers who consider their phones and tablets personal devices they have had since elementary school. They expect high-speed Internet access wherever they go, all the time. Organizations' ability to restrict their workers' computing options will only continue to decline, especially when this conflicts with productivity  for an always-on workforce.

Mobility challenges security because we can no longer rely on managing the devices or networks used to access sensitive resources. Our ability to manage the user experience is also restricted to whatever features the mobile device manufacturers decide to support. Raw market forces drive companies to appeal to us first as *consumers* rather than employees/workers, with high rates of innovation and appealing design that sometimes conflict with corporate control.

##Reinforcing Disruptions

These two trends reinforce each other strongly. The cloud enables mobility by no longer freeing enterprise assets from their reliance on a fixed data center. Mobility in turn drives additional cloud adoption to meet user demand. Both rely on (and drive demand for) ubiquitous high-quality Internet access. Mobile devices become portals to the cloud, and the cloud becomes the engine for mobile applications and services.

Each of these innovations upends older notions of computing and seriously interferes with classical information security strategies. But their reinforcing nature, and strong economic drivers for their continuing advancement, are completely transforming how we deliver and consume technology. Look toward leading consumer web properties as models of how we will architect applications and services in the future.

*We are simultaneously centralizing delivery with the cloud, and decentralizing access with mobile.*

##Impacts on Security

We have hinted at impacts on security practices, but want to emphasize that we aren't necessarily entering a period of greater risk -- just one where we need to adjust approaches and shift resources. Some risks increase, others decrease, and innovative new security approaches leverage these disruptions.

As we migrate more to the cloud (all forms of cloud computing -- Infrastructure, Platform, and Software as a Service) security needs to adjust to new operational realities. Some of this is due to greater reliance on external providers, and some due to inherent technical differences -- especially abstraction and automation.

Greater reliance on external providers means greater reliance on their inherent security. Capabilities vary greatly, placing a greater burden on cloud consumers to assess and audit providers. This can improve relative security -- especially when using cloud providers for whom security is a priority. Providers have a strong incentive to maintain best-in-class security, because failures destroy their ability to maintain client trust and grow their customer base.

Some security issues even decline in the cloud. For example networking sniffing is largely impossible, the dynamic nature of cloud servers can remove the need for traditional patching (you can launch a new fully up-to-date server and shift live traffic to and from it with API calls), and network segmentation becomes the default. Centralizing resources improves our ability to audit and control, while still providing ubiquitous access.

But some risks increase. The cloud management plane allows anyone with network access and credentials to manage your entire infrastructure -- including platforms and applications. We need to rely more on Identity and Access Management controls to segment out users and administrators within cloud services, then integrate them back into our organizations.

Other security controls are fundamentally different in the cloud. We lose our ability to stick physical boxes in front of infrastructure and applications, but gain greater ability to integrate and manage security into the infrastructure itself. Automation creates dynamic environments where servers might exist for only short periods of time (between scanning windows), but we can insert current security agents and configurations at runtime.

Then we layer on mobility. We start to lose control of endpoint access, while also relying more on extending apps (not just email and web pages) to devices in order to support employee workflow needs and expectations. Fortunately these platforms break old operating system models and can be far more secure than laptops and desktops. But employees often own their devices, so we need to put more effort into compartmentalizing enterprise data.

This forces us to rely on security capabilities enabled by the mobile device developer, adjusting *our* security to fit *their* supported models. These devices have proven that locked-down heavily sandboxed environments offer real-world security benefits, but at the same time they limit our ability to load custom security controls. They are more secure but less controlled.

##A twenty-year global technology transformation project

We are only at the very beginning of these disruptive trends. Over the next ten to twenty years they will fundamentally alter how we consume and deliver technology, in ways we cannot fully predict.

Some trends are clear. Use of the cloud will continue, and the economics alone are enough to make it the dominant technology delivery model (especially public cloud). This will centralize more resources and responsibility on Internet providers, shifting security responsibilities and disrupting existing security control models. It also enables new operational models such as DevOps, which challenge existing security and compliance expectations.

Simultaneously, as we consolidate in the cloud we diversify with mobile devices. Social and economic forces will only increase the proliferation of personal devices, along with worker expectations for access to enterprise resources. Organizations can no longer depend on controlling devices or network access -- again shifting security needs.

In the long run, these shifts appear likely to have a greater impact than our initial adoption of the Internet.
