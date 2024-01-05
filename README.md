# Ingenious Way to Update Passwords for Devices at Once — No Vault Needed!
    In today’s rapidly evolving technological landscape, managing security and efficiency are paramount concerns for organizations with fleets of embedded Linux devices. Regularly updating passwords across multiple devices, while ensuring convenience and reliability, can be a complex task.
    Hence, I leveraged the power of Ansible to create an interactive playbook that changes passwords on multiple embedded Linux machines simultaneously.

    -   Repo:
        <https://github.com/pradeepbabar31/cisco_projects.git>


# Tested Ansible Versions
-----------------------

    This collection is tested with the most current Ansible releases.

# Python Version
--------------

    The minimum python version for this collection is python 3.8.

# Installation
------------


    Clone the repo
    ```bash
    git clone https://github.com/pradeepbabar31/cisco_projects.git
    ```
    Go to your project folder
    ```bash
    cd cisco-projects
    ```

    Set up a Python venv
    First make sure that you have Python 3 installed on your machine. We will then be using venv to create an isolated environment with only the necessary packages.

    Install virtualenv via pip
    ```bash
    pip install virtualenv
    ```

    Create the venv
    ```bash
    python3 -m venv venv
    ```

    Activate your venv
    ```bash
    source venv/bin/activate
    ```
    * No need to Install any other dependencies/collection/module to use this Ansible Playbook 


# Usage
-----

    Refer below command line for usage: 

    $ ansible-playbook -i inventory multiple_pass_change.yml -e "hostlist=cisco_device_host_ip" "-u=root" -k -K


    -k, --ask-pass        ask for device SSH connection password (ssh)
    -K, --ask-become-pass ask for privilege escalation password if needed



# Releasing, changelogs, versioning and deprecation
-------------------------------------------------
    There is currently no intended release frequency for major and minor versions. The intended frequency of patch versions is never, they are released for fixing issues or to address security concerns.


[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/8274/badge)](https://www.bestpractices.dev/projects/8274)
or by embedding this in your HTML:
<a href="https://www.bestpractices.dev/projects/8274"><img src="https://www.bestpractices.dev/projects/8274/badge"></a>
