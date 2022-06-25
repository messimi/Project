
step1; created EC2 instances with the default security group 0.0.0.0/

step2; install Apache using Ubuntu's package manager 'apt' and also verify if the apache2 is running as a service in my OS.

step; Add a rule to EC2 configuration to open inbound connection through port 80: that web browser use to access web page on the internet.

step3; check if the server is running and access it locally from the internet (source 0.0.0.0/0 means 'from any ip address')

step4; check if the Apache HTTP server can respond to request from the internet

step5; retrieve my public IP address from server using the curl command


