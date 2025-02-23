<h1>
  <span class="headline">Network Update Lab</span>
  <span class="subhead">Assessing the Current Network State</span>
</h1>

## Assessing the Current Network State

Our client, General Inc., has tasked us with bringing their network infrastructure into the 21st century. They want faster speeds, better security, and the ability to support all those shiny new applications their teams are dreaming up.

Here's what we know about General's current network setup:

- They have a main office with about 500 employees, plus two smaller branch offices with 50 employees each.

- The main office network is built on aging Cisco Catalyst 3750 series switches, with a mix of 100Mbps and 1Gbps ports.The core switch is a Catalyst 4500.

- Branch offices are connected to the main office via 50Mbps MPLS links.

- They're using a mix of legacy Cisco 2900 series routers and newer Meraki MX84 appliances for routing and security.

- Wireless is provided by a hodgepodge of older Cisco Aironet APs and newer Meraki MR33 APs, managed through the Meraki dashboard.

- Servers are a mix of on-prem and AWS EC2 instances, with site-to-site VPNs connecting the office networks to AWS VPCs.

- End-user devices are a mix of Windows 10 PCs and MacBooks, plus a growing fleet of iOS and Android mobile devices.

General's IT leadership has identified the following key requirements and goals for the network update:

1. Upgrade core network infrastructure to support 10Gbps speeds throughout the main office.

2. Improve redundancy and failover for key network links and devices.

3. Implement segmentation to isolate different departments and reduce the blast radius of potential security incidents.

4. Migrate more services and workloads to AWS, while ensuring secure and reliable connectivity between on-prem and cloud resources.

5. Streamline management and monitoring of network devices, servers, and applications.

6. Enhance wireless coverage and performance to support the increasing number of mobile and IoT devices.

7. Strengthen overall network security posture, with a focus on intrusion prevention, data loss prevention, and secure remote access.

Your mission is to develop a comprehensive proposal for updating General's network to meet these requirements and position them for future growth.

Here are some key areas to investigate as you assess General's current network state:

- **Network Topology:** Map out the physical and logical layout of the network. What kind of devices are in use? How are they connected? Are there any single points of failure?

- **Performance Metrics:** Gather data on bandwidth usage, latency, throughput, and error rates. Are there any bottlenecks or problem areas?

**Security Posture:** Evaluate the network's current security measures. Are they running the latest firmware and patches? How are they handling access control and data protection?

**Future Needs:** Talk with General's leadership and IT teams to understand their goals and growth plans. What new capabilities will the network need to support?

Document your findings in a clear, concise report. This will serve as the foundation for your network update proposal. Remember, you can't chart a path forward until you know where you're starting from!
