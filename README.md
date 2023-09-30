# How to deploy a Wordpress Website on AWS Lightsail



Get your website up and running in 5 minutes with these few steps

Let's get started!

**Step 1**

- Login to the Amazon console and Launch Lightsail

- Click on create instance

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/8ccea6e8-4e53-40a5-99ac-020939024774)


**Step 2**

- Select a Region
- Select an Availability Zone

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/3167c534-970e-4498-b4e9-8f682fd36f66)


**Step 3**

- Choose an instance image
- Select Linux/Unix as the platform.
- Select WordPress as the blueprint.

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/2e0970ac-c4d2-4626-980e-d155ed0e6fde)


**Step 4**
- Choose an instance plan

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/5d2b6576-cd80-4cf9-998f-1a36d940ce90)


**Step 5**
- Specify a name for the instance

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/9532d07c-b757-4269-a9cc-cf4c34e46d45)


Our instance has been launched successfully

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/415ab1c1-158d-423c-9f13-68ef19738ad8)


**Step 6**

- Let's connect to our instance
- Choose the SSH quick-connect icon for your WordPress instance.
- After the browser-based SSH client window opens, enter the following command to retrieve the default application password:

```
cat $HOME/bitnami_application_password
```

- Keep the password displayed on the screen. You use it later to sign in to the administration dashboard of your WordPress website

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/1d44a3e9-c089-4892-b645-3d024dbfaf0b)


**Step 7**

- Sign in to the admin console of WordPress
- Copy the link below to a web browser


```
http://PublicIpAddress/wp-login.php
```

- Replace PublicIpAddress with the public IP address of your WordPress instance.

- Log in to your instance

- In the username field enter "user"

- In the Password box, enter the default password obtained earlier then login

Viola!

You are now signed in to the administration dashboard of your WordPress website where you can perform administrative actions.

![image](https://github.com/helloAirX/Wordpress-on-AWS-Lightsail/assets/113798625/6a7b8eca-f040-44c2-b2f3-f6dee7948af5)
