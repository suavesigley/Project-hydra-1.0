Goal: To transform the Toshiba Satellite laptop into a functional file server and central hub for my home network, enabling file sharing and centralising resources.

Key Tasks:

Installed and configured Samba, a key tool for file sharing between Linux and Windows.

Created a dedicated shared folder on the Ubuntu server.

Granted network access to two other laptops, demonstrating basic access control.
<table>
    <caption>My IT Home Lab: PCs samba start up issues</caption>
  <tr>
    <td>
      <img src="images/p1.13.jfif" width="100%" alt="Alt text for image 1">
    </td>
    <td>
      <img src="images/p1.12.jfif" width="100%" alt="Alt text for image 2">
    </td>
    <td>
      <img src="images/p1.10.jfif" width="100%" alt="Alt text for image 3">
    </td>
    <td>
      <img src="images/p1.11.jfif" width="100%" alt="Alt text for image 4">
    </td>
  </tr>
</table>
The Process
With Ubuntu Server installed on the Toshiba, the next step was to configure it as a file server. This required a piece of software called Samba, which allows Linux to share files and printers with Windows, macOS, and other operating systems over a network.

The first step was to install the Samba package using the following command in the terminal:

sudo apt install samba
<table>
    <caption>My IT Home Lab: PCs samba issues</caption>
  <tr>
    <td>
      <img src="images/7c310b63-1e25-41a6-8445-bfc9d29f4779.jfif" width="100%" alt="Alt text for image 1">
    </td>
    <td>
      <img src="images/8bc1fbd9-3117-4cd1-b1e3-fa7496ed694c.jfif" width="100%" alt="Alt text for image 2">
    </td>
    <td>
      <img src="images/p1.15.jfif" width="100%" alt="Alt text for image 3">
    </td>
    <td>
     # <img src="images/p3.2.jfif" width="100%" alt="Alt text for image 4">
    </td>
  </tr>
</table>
Once installed, I had to edit the main configuration file, smb.conf, to create a new network share. I defined the path to a folder, gave it a name, and set the permissions to allow access. This is a crucial step in ensuring that the file server is both functional and secure.

Finally, I created user accounts on the server and granted them access to the shared folder. This allowed my two other laptops to connect to the Toshiba and access the shared files over the network. I could then use this shared space to store important project files, documents, and backups from my other home lab machines, centralising my data and simplifying my workflow.
<table>
    <caption>My IT Home Lab: samba up and running</caption>
  <tr>
    <td>
      <img src="images/p3.0.jfif" width="100%" alt="Alt text for image 1">
    </td>
    <td>
      <img src="images/p1.15.jfif" width="100%" alt="Alt text for image 2">
    </td>
  </tr>
</table>
Outcome
The Toshiba Satellite is now a reliable, centrally managed file server. This phase of the project demonstrated my ability to install and configure software, edit complex configuration files, and manage user permissions—all essential skills for a help desk or systems administration role.
