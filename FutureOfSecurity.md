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

Workers don't wait to be issued a corporate phone -- they walk in the door with a computer in their pocket more powerful that what was on the desks five years ago. They expect to access email and other corporate services from wherever they are, on whatever device they have. Some organizations are able to limit this somewhat, but we see generations of workers who consider their phones and tablets personal devices they have had since elementary school. They expect high-speed Internet access wherever they go, all the time. Organizations' ability to restrict their workers' computing options will only continue to decline, especially when this conflicts with productivity for an always-on workforce.

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

#Six Trends Changing the Face of Security

The cloud and mobile computing are upending the foundational technological principles of delivery and consumption, and at the same time we see six key trends within security itself which promise to completely transform its practice over time. These aren't disruptive innovations so much as disruptive *responses* and incremental *advances* that better align us with where the world is heading.

When we align these trends with advances in and adoption of cloud and mobile computing, we can picture how security will look over the next seven to ten years.

##Hypersegregation

We have always known the dramatic security benefits of effective compartmentalization, but implementation was typically costly and often negatively impacted other business needs. This is changing on multiple fronts as we gain the ability to heavily segregate, by default, with minimal negative impact. Flat networks and operating systems will not only soon be an artifact of the past, but difficult to even implement.

Hypersegregation makes it much more difficult for an attacker to extend their footprint once they gain access to a network or system, and increases the likelihood of detection.

Most major cloud computing platforms provide cloud-layer software firewalls, by default, around every running virtual machine. In cloud infrastructure, every single server is firewalled off from every other one by default. The equivalent in a traditional environment would be either a) host-based firewalls on every host, of every system type, with easily and immediately managed policies across all devices, or b) putting a physical firewall in front of every host on the network, which travels with the host if and when it moves.

These basic firewalls are managed via APIs, and by default even segregate every server from every other server -- even on the same subnet. There is no such thing as a flat network when you deploy onto Infrastructure as a Service, unless you *work hard* to reproduce the less secure architecture.

This segregation has the potential to expand into non-cloud networks thanks to *Software Defined Networking,* making hypersegregation the default in any new infrastructure.

We also see hypersegregation working extremely effectively in operating systems. Apple's iOS sandboxes every application by default, creating another kind of 'firewalls' *inside* the operating system. This is a major contributor to iOS's complete lack of widespread malware -- going back to the iPhone debut seven years ago. Apple now extends similar protection to desktop and laptop computers by sandboxing all apps in the Mac App Store.

Google sandboxes all tabs and plugins in the Chrome web browser. Microsoft sandboxes much of Internet Explorer and supports application level sandboxes. Third-party tools extend sandboxing in operating systems through virtualization technology.

Even application architectures themselves are migrating toward further segregating and isolating application functions to improve resiliency and address security. There are practical examples today of task and process level segregation, enforcing security policy on actions by whitelisting.

The end result is networks, platforms, and applications that are more resistant to attack, and limit the damage of attackers even when they succeed. This dramatically raises the overall costs of attacks while reducing the necessity to address every vulnerability immediately or face exploitation.

##Operationalization of Security

Security, even today, still performs many rote tasks that don't actually require security expertise. For cost and operational efficiency reasons, we see organizations beginning to hand off these tasks to Operations to allow security professionals to focus on what they are best at. This is augmented by increasing automation capabilities -- not that we can ever eliminate the need for humans.

We already see patch and antivirus management being handled by non-security teams. Some organizations now extend this to firewall management and even low-level incident management. Concurrently we see the rise of security automation to handle more rote-level tasks and even some higher-order functions -- especially in assessment and configuration management.

We expect Security to divest itself of many responsibilities for network security and monitoring, manual assessment, identity and access management, application security, and more. This, in turn, frees up security professionals for tasks that require more security expertise -- such as incident response, security architecture, security analytics, and audit/assessment.

Security professionals will play a greater role as subject matter experts, as most repetitive security tasks become embedded into day-to-day operations, rather than being a non-operations function.

##Incident Response

One of the benefits of the increasing operationalization of security is freeing up resources for incident response. Attackers continue to improve as technology further embeds itself into our lives and economies. Security professionals have largely recognized and accepted that it is impossible to completely stop attacks, so we need greater focus on detecting and responding to incidents. This is beginning to shift security spending toward IR tools and teams, especially as we adopt the cloud and platforms that reduce our need for certain traditional infrastructure security tools.

Leading organizations today are already shifting more and more resources to incident detection and response. To [react faster and better, as we say here](https://securosis.com/assets/library/reports/Securosis-RFAB_FINAL.pdf). Not simply having an incident response plan, or even tools, but conceptually re-prioritizing and re-architecting entire security programs -- to focus as much or more on detection and response as on pure defense. We will finally use all those big screens hanging in the SOC to do more than impress prospects and visitors.

A focus on incident response, on more rapidly detecting and responding to attacker-driven incidents, will outperform our current security model -- which is overly focused on checklists and vulnerabilities -- affecting everything from technology decisions to budgeting and staffing.

##Software Defined Security

Today security largely consists of boxes and agents distinct from the infrastructure we protect. They won't go away, but the cloud and increasingly available APIs enable us to directly integrate and manage infrastructure, rather than attempting to protect it only from the outside. Security will rely more on tools and techniques to connect infrastructure to our security tools and management directly, enabling adaptive and effective *security orchestration*.

Software Defined Security is a natural outcome of increasing cloud computing usage, where the entire infrastructure, platforms, and applications are managed using APIs. Security can now directly manage exposed security features using the same APIs, and better integrate security tools into orchestrated environments when security tools themselves offer APIs.

This is very different to how most security tools function today, when many vendors silo off their products and restrict interoperability. But we already see growing pressure on security vendors to extend API support -- especially for products being deployed with cloud computing.

We gain incredible security automation capabilities, such as [this example of automating security configuration policy enforcement](https://securosis.com/assets/library/reports/SDS-Practical-Example.pdf). Imagine being able to instantly identify all unmanaged servers in your cloud, without scanning. Or automatically assessing new systems for vulnerabilities when they first boot or connect to the network, and quarantine them if they fail certain checks. In a few weeks we were even able to write a program that [completely automates most incident response and forensics tasks for a compromised cloud server, in a few seconds](https://github.com/Securosis/SecuritySquirrel). We suspect a real programmer, rather than an industry analyst, could have completed it in a fraction of the time.

Software Defined Security automates security tasks for more agile security infrastructure. It bridges and orchestrates multiple security products with our environments, supporting a security management plane that operates at cloud speed and scale.

##Active Defense

The old saying in security is that a defender needs to be right every time, while an attacker only needs to be right once. Active defense reverses this concepts and *forces attacker perfection*. It dramatically increases the cost of attack, and is strongly reinforced by hypersegregation, the operationalization of security, and Software Defined Security -- while in turn becoming a cornerstone of incident response.

As explained by [the Data Breach Triangle](https://securosis.com/blog/the-data-breach-triangle/), an attacker needs a way in, something to steal or damage, and a way back out. Characterizing attackers and then tracking and understanding their activity is difficult even with extensive monitoring, but active defense technologies validate attackers by allowing the infrastructure and applications to interact with them directly, identifying them far more accurately than with monitoring alone. This way even if an attacker is initially successful, the slightest mistake can enable us to detect and contain them. Responsive, automated defenses interact with attackers to reduce false positives and negatives.

Instead of relying on out-of-date signatures, poor heuristics prone to false positives, or manual combing through packets and logs, we will instead build environments so laden with tripwires and landmines that they would be banned by the Geneva Convention. Heuristic security tends to fail because it often relies on generic analysis of good and bad behavior which is difficult or impossible to model -- active defenses interact with intruders while complicating and obfuscating their view of underlying structure. Dynamic interaction is far more likely to properly identify and classify an attacker.

Active defenses will become commonplace, and largely replace our current signature-based systems of failure.

##Closing the Action Loop

Managing security today is a complicated dance, jumping between disconnected tools. Not that we lack dashboards and management consoles, but they still reside in silos -- incapable of providing effective and coordinated security analysis and response. We call the process of detection, analysis, and action the *Action Loop* (yes, it is based on the military [OODA loop](http://en.wikipedia.org/wiki/OODA_loop)).

Current tools largely fall into general functional categories which are too distinct and isolated to satisfy our requirements. Some tools observe the environment (such as SIEM, DLP, and full packet capture), but they tend to focus on narrow slices -- with massive gaps between tools, which hamper our ability to acquire related information we need to understand incidents. From an alert we need to jump into many different shells and command lines on multiple servers and appliances in order to see what's really going on. When tools talk to each other it is rarely in a meaningful and useful way.

While some tools support automation, it is again self-contained, uncoordinated, and (beyond the most simplistic incidents) more prone to break a business process than stop an attacker. When we want to perform a manual action our environments are typically so segregated and complicated that we can barely manage something as simple as pushing a temporary firewall rule change.

Recently we have seen tools emerging which are just beginning to deliver on our old dreams, once shattered by the ugly reality of SIEM. These tools combine the massive amounts of data we are currently collecting on our environments, at speeds and volumes long promised but never realized. We will steal analytics from big data; tune them for security; and architect systems that allow us to visualize our security posture, identify, and rapidly characterize incidents.

From the same console we will be able to look at a high-level SIEM alert, drill down into the specifics, and analyze correlated data from multiple tools and sensors.

No, your current SIEM doesn't do this.

But the clincher is the closer. Rather than merely looking at incident data, we will *act* on data using the same console. We will review automated responses, model their possible impact with analytics and visualization (real-time attack and defense modeling, based on near-real-time assessment data), and then tune and implement additional actions to contain, stop, and investigate attacks.

Detection, investigation, analysis, orchestration, and action all from the same console.

##Disruptive Reinforcement

These inherent security trends not only build and reinforce each other -- they are in turn supported by increasing adoption of cloud and mobile technology (and to a lesser degree big data). We don't see these as pie in the sky predictions, but logical extensions of existing advances and changes in the practice of security.

They are not, however, evenly distributed. Although we see some organizations adopting most or all of these technologies and practices, it will likely be a decade or more before they become common throughout the security market. The end state may be a logical conclusion, but there are many paths there -- both slow and quicker.

But some risks increase. The cloud management plane allows anyone with network access and credentials to manage your entire infrastructure -- including platforms and applications. We need to rely more on Identity and Access Management controls to segment out users and administrators within cloud services, then integrate them back into our organizations.

Other security controls are fundamentally different in the cloud. We lose our ability to stick physical boxes in front of infrastructure and applications, but gain greater ability to integrate and manage security into the infrastructure itself. Automation creates dynamic environments where servers might exist for only short periods of time (between scanning windows), but we can insert current security agents and configurations at runtime.

Then we layer on mobility. We start to lose control of endpoint access, while also relying more on extending apps (not just email and web pages) to devices in order to support employee workflow needs and expectations. Fortunately these platforms break old operating system models and can be far more secure than laptops and desktops. But employees often own their devices, so we need to put more effort into compartmentalizing enterprise data.

This forces us to rely on security capabilities enabled by the mobile device developer, adjusting *our* security to fit *their* supported models. These devices have proven that locked-down heavily sandboxed environments offer real-world security benefits, but at the same time they limit our ability to load custom security controls. They are more secure but less controlled.

##A twenty-year global technology transformation project

We are only at the very beginning of these disruptive trends. Over the next ten to twenty years they will fundamentally alter how we consume and deliver technology, in ways we cannot fully predict.

Some trends are clear. Use of the cloud will continue, and the economics alone are enough to make it the dominant technology delivery model (especially public cloud). This will centralize more resources and responsibility on Internet providers, shifting security responsibilities and disrupting existing security control models. It also enables new operational models such as DevOps, which challenge existing security and compliance expectations.

Simultaneously, as we consolidate in the cloud we diversify with mobile devices. Social and economic forces will only increase the proliferation of personal devices, along with worker expectations for access to enterprise resources. Organizations can no longer depend on controlling devices or network access -- again shifting security needs.

In the long run, these shifts appear likely to have a greater impact than our initial adoption of the Internet.
