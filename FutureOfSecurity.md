#A Disruptive Collision

At the best of times, the practice of information security is defined by disruption. Forced to respond to the business and technology innovations not only of those we defend, but of those attacking them. Security is never really in control of our own destiny since we are tasked with managing the risks of decisions made by others, in the face of entire industries (and economies) dedicated to discovering new ways of stealing or hurting us. We are reactive because those we protect and those who attack are never fully predictable, not because of an inherent failing of security.

However, the better we predict these disruptions, and the better we prepare our response, the more effective we are. 

As analysts, we at Securosis focus most of our research on the here and now; on how to best tackle the security challenges faced by CISOs and security professionals when they show up to work in the morning. On occasion, as part of this research, we note trends with the potentially to dramatically affect the security industry and profession. 

We currently see what is likely the biggest collision of disruptive forces since the initial adoption of the Internet; one with implications for security far *beyond* our first steps onto the global network. Simultaneously, we have identified six key trends altering the practice of security, independent of these forces. This combination of external and internal change is already fundamentally transforming the practice of security.

This paper starts with a description of the disruptive forces and the native security trends, but its real objective is to lay out the long-term implications on the practice of security and how we expect it to evolve for security professionals, security vendors, and cloud and other infrastructure providers. Throughout the report we back up our analysis with real-world examples that show this transformation isn't some far-off future, but is already occurring today.

But although these changes are inevitable, they are far from evenly distributed. As you will see this provides plenty of time and incentive for most professionals and organizations to prepare.

##Two Disruptive Innovations

Clayton Christensen first [coined the term "disruptive technology" in 1995](http://en.wikipedia.org/wiki/Disruptive_innovation) (and later changed the term to "disruptive innovation") to describe new business and technology practices that fundamentally alter, and eventually supersede, existing ones. Innovation always induces change, but *disruptive innovation mandates change*. Once the innovation hits, it creates new opportunities, and disrupts the old.

The technology world is experiencing a combination of two disruptive innovations simultaneously colliding and reinforcing each other. *Cloud computing* alters the consumption and delivery models for technology at both economic and technical levels. At the same time, advances in *mobile technology* reinforce the need for cloud,  while changing our access and consumption models, particularly at scale. 

###Cloud Computing  

Cloud computing is a radically different technology model -- not just the latest flavor of outsourcing. It uses a combination of *abstraction* and *automation* to achieve previously impossible levels of efficiency and elasticity. This, in turn, creates new business models and alters the economics of technology delivery and consumption.

Sometimes this means building your own cloud in your own datacenter; other times it means renting infrastructure, platforms, and applications from public providers over the Internet. Public cloud services eliminate most capital expenses, shifting them to on-demand operational costs instead. Private clouds allow more *efficient* use of capital, may reduce operational costs, and make technology more responsive to internal needs. 

Cloud computing fundamentally disrupts traditional infrastructure because it is more responsive, more efficient, and potentially more resilient and cost effective than our old ways of doing things. These are the same drivers that pushed us towards application service providers and virtualization. Public cloud computing is even more disruptive, since it allows organizations to consume only what they need, without maintaining overhead, and still rapidly respond to changing needs at effectively infinite scale (with a big enough checkbook).

Every major enterprise we talk with today uses cloud services, and even some of the most sensitive industries, like financial services, are exploring more extensive use of public cloud computing. We see no technical, economic, or even regulatory issues to slow the trend 

Although many security professionals focus on the multitenancy risks introduced by cloud, *abstraction* and *automation* are more impactful than shared infrastructure or services. Many of our security controls today rely on knowing and managing the underlying physical resources that create the technology services we consume. Abstraction breaks this model by virtualizing resources (including entire applications) into resource pools we manage over the network. We give up physical control, and shift management functions to standard network interfaces, creating a new *management plane*. This separation and remote management challenge or destroy unmodified traditional security controls.

Abstraction is core to virtualization, and we are at least nominally familiar with the issues. Automation is distinct to the cloud, and adds an orchestration layer to most efficiently utilize the resource pools. It allows for massive agility, such as servers that exist only for hour or minutes, automatically provisioned, configured, and destroyed without human interaction. Applications developers can check in a piece of code, which then runs through a dozen automated checks and is pushed into production on a self-configuring platform that scales to meet demand. Security that relies on controlling the rate of change, or that mandates human checks, can't keep up with this agility. 

Virtualization is the core enabling technology of abstraction, and Application Programming Interfaces (APIs) the core enabler of automation. The outcomes, elasticity and agility, enable new operational models like *DevOps*, which consolidate historically segregated management functions to improve efficiency and responsiveness. Combine with a greater reliance on public cloud computing, and the Internet itself becomes the interconnected platform for our applications and workloads.

>Defining DevOps
>
>DevOps is [an IT model that blurs the lines between development and IT operations.](http://en.m.wikipedia.org/wiki/Devops) Developers play a stronger role in managing their own infrastructure through heavy use of programming and automation. Since cloud enables management of infrastructure using APIs, it is a major enabler of DevOps. While it is incredibly agile and powerful, lacking proper governance and policies it can also be disastrous since it condenses many of the usual application development and operations check points.

These changes aren't bad or inherently riskier. They do, however, require new approaches. In some cases, they offer opportunities to wipe out common security issues and shift resources to new priorities.

Between business benefits and current adoption rates, we expect public cloud computing to become the dominant technology model over the next ten to fifteen years. As we make this transition *it is the technology that creates clouds, rather than the increased use of shared infrastructure, that really matters for security*. 

###Mobility

Walk down the street, pull your eyes from your phone, and look around you. In less than a decade we moved from most technology services being accessed from desktop and laptop computers, to being accessed from mobile devices with near-ubiquitous wireless high-speed networks. It's hard to fully comprehend how rapidly this shift occurred, and the implications.

Workers don't wait to be issued a corporate phone, they walk in the door with a computer in their pocket more powerful that what was likely on their desk five years ago. They expect to access email and other corporate services from wherever they are, on whatever device they have. Some organizations are able to limit this somewhat, but we now see generations of workers who consider their phones and tablets personal devices they've had since elementary school. They expect high-speed Internet access wherever they go, at all times. The ability for organizations to restrict the computing options of workers will only continue to decrease, especially if it interferes with productivity increases of an always-on workforce.

Mobility challenges security because we can no longer rely on managing the device used to access resources, nor the networks they use. Our ability to manage the user experience is also restricted to whatever features the mobile device manufacturers decide to support. Raw market forces alone push these companies into appealing to us first as consumers, not workers, with high rates of innovation and appealing design sometimes incongruous with corporate desires for control.

##Reinforcing Disruptions

These two trends strongly reinforce each other. Cloud enables mobility by no longer tying enterprise assets to a fixed data center. Mobility, in turn, drives additional cloud adoption to meet user demand. Both rely on ubiquitous Internet access and anywhere, anytime, low-lag connectivity. Mobile devices become the portal to the cloud, while the cloud is the engine for mobile applications and services.

Either of these innovations alone massively disrupts our previous notions of computing and our strategies for information security. But the reinforcing nature, and strong economic drivers to continue their advancement, are completely transforming how we deliver and consume technology. Look towards the models of the leading consumer web properties today to understand how all of us will architect our applications and services in the future. 

*We are simultaneously centralizing delivery with cloud, and decentralizing access with mobile.*

##Impacts on Security

We've hinted at some of the impacts on security practices, but want to emphasize that we aren't necessarily entering a period of greater risks, just one where we need to adjust our approaches and shift resources. Some risks do increase, but others decrease, and we are seeing innovative new security approaches that leverage the advantages of these disruptions.

As we migrate more to the cloud (and we include all forms of cloud computing — Infrastructure, Platform and Software as a Service) security has to adjust to the new operational realities. Some of this is due to a greater reliance on external providers, and some due to inherent technical differences,  especially abstraction and automation.

A greater reliance on external providers translates to a greater reliance on the inherent security of those providers. Capabilities vary greatly, placing a greater burden on cloud consumers to assess and audit their providers. In some cases this improves relative security, especially when using cloud providers that prioritize security. Providers have a strong incentive to maintain best-in-class security since failures destroy the ability to maintain the trust of clients and grow the customer base. 

Some security issues even decline in the cloud. For example, networking sniffing is generally eliminated, the more dynamic nature of cloud servers upends traditional notions of patching (since you can launch a new, fully up to date server and migrate live traffic with a few API calls), and network segmentation becomes the default. Centralizing resources improves our ability to audit and control, while still providing ubiquitous access.

However, some risks increase. The cloud management plane allows anyone with network access and proper credentials to manage your entire infrastructure, platforms, and applications. We need to rely more on Identity and Access Management controls to segment out users and administrators within the cloud services, then integrate these back into our organizations. 

Other security controls are fundamentally, altered. We lose the ability to stick physical boxes in front of our infrastructure and applications, but gain greater abilities to integrate and manage security into the infrastructure itself. Automation creates dynamic environments where servers might exist for only short periods of time between scanning windows, but we can insert security agents and configurations at run time.

Then we layer on mobility. We start to lose control of the endpoint access, while also relying more on extending apps (not just email and web pages) to devices in order to support employee workflow needs and expectations. One advantage is that these platforms break old operating system models and can be far more secure than a laptop and desktop. However, since employees often own their devices, more emphasis is on compartmentalizing enterprise data.

This forces us to rely on the security capabilities enabled by the mobile device manufacturer, and adjusting our security to fit their supported models. These devices have proven that locked down, heavily sandboxed environments demonstrate real-world security benefits, but that concurrently reduces the ability for enterprises to load up the devices with custom security controls. They are more secure, but less controlled.

##A twenty year global technology transformation project  

We are only at the very beginning of these disruptive trends. Over the next ten to twenty years they will fundamentally alter how we consume and deliver technology, in ways we can't fully predict. 

Some trends are clear. The use of cloud will continue, and for economic reasons alone it will likely become the dominant technology delivery model (especially public cloud). This centralizes more resources onto Internet providers, shifting security responsibilities and disrupting existing security control models. It enables new operational models like DevOps, which challenge existing security *and* compliance expectations.

Simultaneously, as we consolidate in cloud (GS: Comma) we diversify with mobile. Social and economic forces will only increase the proliferation of personal devices, and worker expectations to connect them to enterprise resources. Organizations can no longer depend on controlling devices or network access, again shifting security needs.

The end result of these shifts is likely greater than the impact of our initial adoption of the Internet. 

#Six Trends Changing the Face of Security

While cloud and mobile computing upend our foundational delivery and consumption of technology, we simultaneously see six key inherent trends within  security that will, over time, completely transform its practice. These aren't disruptive innovations, but rather disruptive responses and incremental advances that better align with where the world is heading. 

When we align these trends with the simultaneous advances and adoption of cloud and mobile computing we can build a picture of how security will look over the next seven to ten years.

##Hypersegregation

We have always known the dramatic security benefits of effective compartmentalization, but implementation was typically costly and often negatively impacted other business needs. This is changing on multiple fronts as we gain the ability to heavily segregate, by default, with minimal negative impact. Flat networks and operating systems will not only soon be an artifact of the past, but actually difficult to even implement.

Hypersegregation makes it much more difficult for an attacker to extend their footprint once they gain access to a network or system, while also increasing the chances of detection.

In cloud computing, most major platforms provide cloud-layer software firewalls, by default, around every running virtual machine. In cloud infrastructure, every single server is firewalled off from every other one, by default. The traditional environment equivalent is either managing host-based firewalls (in every host, across system types, with consistent policies that can be externally and instantly managed), or putting a physical firewall in front of every host on the network, that travels with the host as it moves. 

These basic firewalls are managed via API, and by default even segregate every server from every other server in the same subnet. There is no such thing as a flat network when you deploy onto Infrastructure as a Service, unless you try *really hard* to replicate the less secure architecture. 

This segregation has the potential to expand into non-cloud networks thanks to *Software Defined Networking*. Making hypersegregation the default in any infrastructure.

We also see it working extremely effectively in our operating systems. Apple's iOS sandboxes every application by default, deeply segregating the environment. This is a major contributing factor to the complete lack of any widespread malware on iOS since the debut of the iPhone seven years ago. Apple now extends this protection to desktop and laptop computers by sandboxing all apps in the Mac App Store. 

Google sandboxes all tabs and plugins in the Chrome web browser. Microsoft sandboxes much of Internet Explorer, and supports application level sandboxes. Third-party tools exist to extend sandboxing in operating systems through the use of virtualization technology. 

Even application architectures themselves are migrating more towards segregating and isolating application functions to both improve resiliency and address security. There are practical examples today of task and process level segregation, making security decisions on whitelisted actions. 

The end result is networks, platforms, and applications that are more resistant to attack, and limit the damage of attackers even when they succeed. This dramatically raises the overall costs of attacks, while reducing the necessity of addressing every vulnerability immediately or face exploitation.

##Operationalization of Security

Security, even today, still performs many rote tasks that don't actually require security expertise. For cost and operational efficiency we see organizations beginning to hand off these tasks to operations to allow security professionals to focus on what they are best at. This is augmented by increasing automation capabilities, not that we can ever eliminate the need for humans.

We already see patch and antivirus management being handled by non-security teams. Some organizations now extend this to firewall management and even low-level incident management. Concurrently, we see the rise of security automation to handle more rote-level tasks, and even some higher-order functions, especially in assessment and configuration management.

We expect security to shed extensive aspects of network security and monitoring, manual assessments, identity and access management, application security, and more. This, in turn, frees up security professionals for tasks that require more-extensive security expertise, such as incident response, security architectures, security analytics, and audit/assessment. 

Security professionals will play a greater role as subject matter experts as most repetitive security tasks become embedded in to day to day operations, instead of being an outside function.

##Incident Response

One of the benefits of the increasing operationalization of security is a corresponding increase in the resources available for incident response. Attackers continue to improve as technology further embeds itself into our lives and economies. Security professionals have realized that it is impossible to completely stop attacks, and we need a greater focus on detecting and responding to incidents. This is beginning to shift security spending more towards IR tools and teams, especially as we adopt cloud and platforms that reduce our need for certain traditional infrastructure security tools.

Leading organizations today are already shifting more and more resources to incident detection and response. To [reacting faster and better as we like to say here at Securosis](https://securosis.com/assets/library/reports/Securosis-RFAB_FINAL.pdf). Not merely the simple expedient of having an incident response plan, or even tools, but conceptually re-prioritizing and re-architecting entire security programs – to focus as much or more on detection and response as on pure defense. We will finally use all those big screens hanging in the SOC to do more than impress prospects and visitors.

A focus on incident response, on more rapidly detecting and responding to attacker-driven incidents, will exceed our current checklist and vulnerability focused security model, affecting everything from technology decisions to budgeting and staffing.

##Software Defined Security

Today, security largely consists of boxes and agents separate from the infrastructure we protect. While these won't go away, with cloud and the increasing availability of APIs we gain the ability to directly integrate and manage with the infrastructure, as opposed to protecting it only from the outside. Security will rely more on tools and techniques to connect the infrastructure to our security tools and management directly, enabling adaptive and effective *security orchestration*.

Software Defined Security is a natural outcome over the increasing use of cloud computing where the entire infrastructure, platforms, and applications are managed using APIs. Security can now directly manage exposed security features using the same APIs, and better integrate security tools into orchestrated environments when security tools themselves offer APIs.

This is very different to how most security tools function today as many vendors silo off their products and restrict interoperability. However, we already see growing pressure on security vendors to extend API support, especially for products being deployed with cloud computing. 

We gain incredible abilities to automate security, such as [the example in this linked paper for automating security configuration policy enforcement](https://securosis.com/assets/library/reports/SDS-Practical-Example.pdf). Imagine being able to instantly identify all unmanaged servers in your cloud, without scanning. Or automatically vulnerability assessing new systems when they first run or connect to the network, and quarantine them if they fail certain checks. In a few weeks we were even able to write a program that [completely automates most incident response and forensics tasks for a compromised cloud server, in a few seconds](https://github.com/Securosis/SecuritySquirrel). (Something we suspect a real programmer, as opposed to an industry analyst, could have completed in a fraction of the time).

Software Defined Security automates security tasks for a more-agile security infrastructure. It bridges and orchestrates multiple security products with our environments themselves, and supports a security management plane that operates at cloud speed and scale.

##Active Defense

The old saying in security is the defender needs to be right every time, and the attacker only needs to be right once. Active defense reverses this concepts and *forces attacker perfection*. It dramatically increases the cost of attack, and is strongly reinforced by hypersegregation, the operationalization of security, and Software Defined Security while, in turn, becoming a cornerstone of incident response. 

According to [the Data Breach Triangle](https://securosis.com/blog/the-data-breach-triangle/) an attacker needs a way in, something to steal or damage, and a way back out. Characterizing attackers and then tracking and understanding their activity is difficult even with extensive monitoring, but active defense technologies validate attackers by allowing the infrastructure and applications to interact with them directly, identifying them far more accurately than with monitoring alone. Now, even if an attacker is successful, they make the slightest mistake and we can detect and contain them. Responsive, automated defenses interact with attackers to reduce false positives and negatives.

Instead of relying on out-of-date signatures, poor heuristics prone to false positives, or manual combing through packets and logs, we will instead build environments so laden with tripwires and landmines that they may end up being banned by a virtual Geneva Convention. Heuristic security tends to fail because it often relies on generic analysis of good and bad behavior that is difficult or impossible to model; active defenses interact with intruders while complicating and obfuscating the underlying structure. This dynamic interaction is far more likely to properly identify and classify an attacker.

Active defenses will become commonplace, and in large part replace our signature-based systems of failure.

##Closing the Action Loop

Managing security today is a complicated dance of jumping between a series of disconnected tools. Not that we lack dashboards and management consoles, but those still reside in silos and are incapable of providing effective, coordinated, security analysis and response. We call the process of detection, analysis, and action the *Action Loop* (and yes, it is based on the concept of the [OODA loop for those of you with a military background](http://en.wikipedia.org/wiki/OODA_loop)). 

Our current tools largely fall into general functional categories that are too distinct and isolated to really meet our needs. Some tools observe our environment (e.g., SIEM, DLP, and full packet capture), but they tend to focus on narrow slices – with massive gaps between tools hampering our ability to acquire related information which we need to understand incidents. From an alert, we need to jump into many different shells and command lines on multiple servers and appliances in order to see what’s really going on. When tools talk to each other, it’s rarely in a meaningful and useful way.

While some tools can act with automation, it is again self-contained, uncoordinated, and (beyond the most simplistic incidents) more prone to break a business process than stop an attacker. When we want to perform a manual action, our environments are typically so segregated and complicated that we can barely manage something as simple as pushing a temporary firewall rule change.

Recently we have seen the emergence of tools just beginning to deliver on the old dreams so shattered by the ugly reality of SIEM. These tools will combine the massive amounts of data we are currently collecting on our environments, at speeds and volumes long promised but never realized. We will steal analytics from big data; tune them for security; and architect systems that allow us to visualize our security posture, identify, and rapidly characterize incidents.

From the same console we will be able to look at a high-level SIEM alert, drill down into the specifics, and analyze correlated data from multiple tools and sensors. 

No, your current SIEM doesn’t do this.

But the clincher is the closer. Rather than merely looking at incident data, we will act on the data using the same console. We will review the automated responses, model the impact with additional analytics and visualization (real-time attack and defense modeling, based on near-real-time assessment data), and then tune and implement additional actions to contain, stop, and investigate the attack.

Detection, investigation, analysis, orchestration, and action all from the same console.

##Disruptive Reinforcement

These inherent security trends not only build and reinforce each other, but are, in turn, supported by increasing adoption of cloud and mobile technology (and, to a lesser degree, Big Data). We don't see these as pie in the sky predictions, but the logical extension of existing advancements and changes in the practice of security.

They are not, however, evenly distributed. Although we see some organizations adopting most or all of these technologies and practices, it will likely be a decade or more before they become common throughout the security market. The end state may be a logical progression, but there are a lot of paths and velocities to get there.