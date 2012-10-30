---
layout: post
title: "Diary for the week of 10/26"
date: 2012-10-28 09:06
comments: true
categories: Diary
published: false
---

* First week without [Brian](http://echosa.github.com) in the office.
  Time to bury myself in my work to get over the pain...just kidding,
  congratulations on your new position at
  [Improving](http://improvingenterprises.com/)!

* New vice president signed off on my promotion.  A background check
  of some sort from HR is pending but I will now refer to myself as
  Senior Lead Software Application Developer.

* Finished filtering UINs for Sherri, was interrupted on Friday by
  bomb threat.
  
* Drafted a reponse to iMedRIS about new features and CAS interoperability

* Met with a consultant from [BlackBoard](http://www.blackboard.com).
  We had a productive meeting about creating a
  [MediaMatrix](http://mediamatrix.tamu.edu) REST API for them to plug
  out campus installation of Learn in to.  I was told that we have the
  best media serving system in regards to authentication and
  authorization that they have seen.  +2 Morale.

* Finished packaging up CAS plugin for iRIS, sent response to Catherine.

* Created a [vagrant](http://vagrantup.com) VM for MediaMatrix.
  Really awesome.  I used [chef](http://www.opscode.com/chef/) for
  system configuration, and I am totally in love.

* I even created a Windows vagrant box using the instructions
  [here](http://geekynotebook.com/creating-windows-base-box-in-vagrant/).
  I ended up going with [CopSSH](https://www.itefix.no/i2/copssh) as
  my Windows SSH server because OpenSSH was just too buggy.  It's nice
  to be dropped into a Bash shell as well.  There is still some work
  to be done as the default vagrant linux base commands don't work on
  Windows.

* Moved the MediaMatrix source into git.  The live server is still
  deployed from Subversion for the time being.  However, with my
  vagrant VM I have been able to test deploy a record number of fixes.
  I live deploy using a git patch to the production SVN tag and all of
  a sudden SVN isn't so much of a pain anymore.
  
