HubDrop Test Repo
=================

This is a repo created for testing HubDrop.io.

This is the first HubDrop repo that is being mirrored *back* to drupal.org.

Switching Directions
====================

Check out your module's project page.  It will tell you what direction hubdrop is 
mirroring your project. 

See http://hubdrop.io/project/hubdrop_test for an example.

To switch direction of the mirror, simply call `hubdrop source`

```
hubdrop@hubdrop:~$ hubdrop source hubdrop_test github
[HUBDROP:dev] Initiating AppKernel...
[SUCCESS] Source set.
hubdrop@hubdrop:~$ 
```

Use `hubdrop source hubdrop_test drupal` to switch it back.

The direction indicator will change at http://hubdrop.io/project/hubdrop_test.
