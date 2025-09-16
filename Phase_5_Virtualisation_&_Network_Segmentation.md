Phase 5: Virtualisation & Network Segmentation
Goal: To establish a virtualised environment on the desktop, creating a private network to safely simulate real-world cyber-attacks. This phase was guided by the book "Ethical Hacking: A Hands-on Introduction to Breaking In" by Daniel G. Graham.

Key Tasks:

Installed and configured VirtualBox as the hypervisor.

Deployed pfSense as the virtual firewall to create a segmented network.

Built and configured three virtual machines: a Kali Linux attacker machine, a vulnerable Metasploitable target, and an Ubuntu user machine.

The Process
With the desktop now a capable server, I moved on to creating a virtual lab. This is a crucial step in ethical hacking because it allows you to practice offensive and defensive techniques without risking damage to a live network. The book "Ethical Hacking" provided a clear roadmap for this process.

First, I installed VirtualBox on the Ubuntu server. VirtualBox is a user-friendly and powerful hypervisor that turns a machine into a virtualisation host. From there, I created a series of virtual machines, each serving a specific role in my lab.

The first VM I set up was pfSense, an open-source firewall distribution. I configured pfSense to act as a virtual router and firewall, creating a separate, secure network for my lab. This is a critical defensive skill that shows how to protect networks and control traffic.

Next, I created a Kali Linux VM. This is my "attacker" machine, equipped with all the penetration testing tools I will need for later phases of the project. I also created a Metasploitable VM, which is intentionally designed with known vulnerabilities. This serves as my "target" machine for practicing exploitation. Finally, I added a standard Ubuntu desktop VM to act as a "user" machine, simulating a typical computer on a network.

Outcome
I successfully built a fully functional virtual lab, demonstrating my ability to use virtualisation for both offensive and defensive purposes. This isolated network allows me to safely experiment with hacking techniques, understand how vulnerabilities are exploited, and learn to protect systems from attack.
