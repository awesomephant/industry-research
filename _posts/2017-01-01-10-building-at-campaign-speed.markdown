---
layout: post
title: "Building applications at campaign speed"
date: 2016-08-16 16:40:39 +0100
categories: article
author: Kyle Rush
publisher: Git Out the Vote
publicationDate: 2016
link: https://medium.com/git-out-the-vote/building-applications-at-campaign-speed-281e802360c2#.nmxp5beq3
---

Kyle Rush is a Deputy Chief Technology Officer at Hillary for America - the organization trying to get Hilary Clinton elected in September. Turns out each page on hillaryclinton.com is a seperate codebase - sounds crazy but it allows them to have different teams working on each and not interfere with each other. 

> To give you an idea of how this works in practice, www.hillaryclinton.com/events, www.hillaryclinton.com/contribute/donate, and www.hillaryclinton.com/ are all separate codebases. This allows the teams that manage events, donate, and the homepage to move independently on their own timeline with their own tech infrastructure. There are many more codebases, but I won’t list them all here.

The problem with this approach is making sure the different pages look and function at least somewhat consistent. Their solution is to have re-usable components both development and design wise that each team uses to build their applications - a bit like lego bricks. Rush on this:

> This approach introduces a problem though. All three of those codebases have an application that has to look and behave like the others. They share the same design and some of the same features, like login and create account for example. To solve this problem we write modular code. The design problem is solved by our own 100% custom built UI bootstrap and component library (code named Pantsuit :). Every new boilerplate project has the library built into it. For many projects our engineers have to write very little and sometimes no CSS at all because of Pantsuit. By just adding Pantsuit classes to HTML elements we have a fully in-brand, ready-to-go interface.

Always fascinating to see how an environment with very specific needs (such as a political campaign) can require very unusual solutions - in every other context making each page of your website a different codebase sounds like madness, but it makes sense here.

