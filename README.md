![I am HubDrop.](http://hubdrop.org/img/logo.png "HubDrop.org")

HubDrop Test Repo
=================

This is a repo created for testing HubDrop.org.

This is the first HubDrop repo that is being mirrored *back* to drupal.org.

When commits are made to https://github.com/drupalprojects/hubdrop_test, if the webhook is working, and jenkins is running, hubdrop server will git pull from github and git push to drupal.org.

Switching Directions
====================

Check out your module's project page.  It will tell you what direction hubdrop is 
mirroring your project. 

See http://hubdrop.org/project/hubdrop_test for an example.

To switch direction of the mirror, simply call `hubdrop source`

```
hubdrop@hubdrop:~$ hubdrop source hubdrop_test github
[HUBDROP:dev] Initiating AppKernel...
[SUCCESS] Source set.
hubdrop@hubdrop:~$ 
```

Use `hubdrop source hubdrop_test drupal` to switch it back.

The direction indicator will change at http://hubdrop.org/project/hubdrop_test.

Setting up WebHook
==================
To connect your repo to github so that it pushes immediately, setup the webhook url https://www.hubdrop.org/webhook

