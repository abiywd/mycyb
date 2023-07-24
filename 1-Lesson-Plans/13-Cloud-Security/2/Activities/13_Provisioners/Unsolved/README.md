## Activity File: Provisioners

- In the previous activities, you finished setting up a jump box that can only be accessed from your current IP address, using your SSH public key.

- In this activity, you will continue to set up a testing environment for XCorp's Red Team.

- Instead of accessing this machine from a local machine, you will only access it from inside the container inside your jump box.

- You are tasked with launching a new VM from the Azure portal that can only be accessed using a new SSH key from the container running inside your jump box.

### Instructions

1. Connect to your Ansible container. Once you're connected, create a new SSH key and copy the public key.

2. Return to the Azure portal locate the details page of your Web-VM.

    - Reset the password for your VM and use your container's new public key for the SSH user.

3. After your VM launches, test your connection using `ssh <vm-username>@<VM-Ip-address>` from your jump box Ansible container and accept the key.

<<<<<<< HEAD
4. Add this machine's _internal IP address_ to the Ansible _hosts_ file.
		- Note: Your Web VM's _should not_ have an external IP address. If they _do_ have an external IP address, it can be ignored.

5. Change the Ansible _configuration_ file to use your administrator account for SSH connections.
=======
4. Add this machine's **internal IP address** to the Ansible **host's** file.

	- Note: Your Web VMs **should not** have an external IP address. If they **do** have an external IP address, it can be ignored.

5. Change the Ansible **configuration** file to use your administrator account for SSH connections.
>>>>>>> 8dbd11e1b6308442aac1e17388e8d1dd6c3c8679

	- **HINT:** Remember to add the line: `ansible_python_interpreter=/usr/bin/python3` besides each IP address you enter.

6. Test an Ansible connection using the appropriate Ansible command.

7. Repeat these steps for your second Web-VM.

---
<<<<<<< HEAD
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
=======

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
>>>>>>> 8dbd11e1b6308442aac1e17388e8d1dd6c3c8679
