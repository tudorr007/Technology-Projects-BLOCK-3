# Basic Firewall Configuration

## Task 1 --- Install the Firewall

Run:

    sudo apt install ufw

### Screenshot

(Add screenshot)

------------------------------------------------------------------------

## Task 2 --- Enable the Firewall

Run:

    sudo ufw enable

### Screenshot

(Add screenshot)

### Questions

1.  What message appears after enabling the firewall?
   Firewall is active and enabled on system startup
3.  Why are firewalls important?
   They protect computers from unauthorised acccess and suspicious network traffic

------------------------------------------------------------------------

## Task 3 --- Allow SSH Access

Run:

    sudo ufw allow ssh
    sudo ufw status

### Screenshot

(Add screenshot)

### Questions

1.  What rule was added?
   rule was added to allow SSH connections through the network
3.  Why must SSH be allowed?
   it enables users to securely access and manage computers remotely over a network, without it, a firewall may block remote connections

### Reflection

Explain how firewalls help protect systems from unauthorised access.
