---
publish: true
tags:
  - quartz
  - vault
date: 2024-02-14 00:00
updated: 2024-02-15T08:40:19-06:00
---

> [!Info]
> In the end, <u>I decided not to use quartz.</u> I decided to use obsidian publish to control my note site instead, due to the tighter integrations. However, I will reconsider this when I wish to have even more customizability with my notes.

# Objective

I want to find a way to not use Obsidian Publish, and "self-host" aka. use a cloud service to publish my notes in a fun site. I found [quartz](https://quartz.jzhao.xyz/)  by Jacky Zhao to be a very good option to accomplish this.

# Problem 1: Content
This vault is in a [separate repository](https://github.com/kaedekaneko/Obsidian-Notes) than the quartz code itself, which it was intended for.

## Solutions

### **Attempt 1:** Git Submodules

I will attempt to submodule the code I have. This will be a great option for controlling quartz versions vs. the versions of my documents!

## Resources

I found an [article by Brandon Boswell](https://brandonkboswell.com/blog/Publishing-your-Obsidian-Vault-Online-with-Quartz/) on how to do precisely this...