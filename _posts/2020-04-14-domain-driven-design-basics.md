---
layout: post
title:  "Domain Driven Design Basics"
crawlertitle: "Domain Driven Design Basics"
summary: "Understand what DDD is about. Grasp the fundamentals easily"
date:   2020-04-14 22:45:04 +01000
categories: posts
tags: ['Doman Driven Design', 'DDD', 'Software Design']
author: Cristina Verdi
--

# Domain Driven Design Basics:

## DDD

#### Domain

A domain is a sphere of knowledge or activity

#### Model:

* A system of abstractions representing selected aspects of a domain

* A model distills knowledge and assumptions about a domain

* Some models are good for some problems, the same model can be innapropriate for other solution

* During development, represent multiple models, from multiple problems and transform data back and forth.

* As a team, extract meaningful concepts

#### Ubiquitous language: How we talk about a problem is fundamental to find a good solution.

* UL is a language structured around the domain model and used by all team members to connect all the activities of the team with the software... within a bounded context.

#### Why model?

The critical complexity of many software projects is in understanding the domain itself.

Having a model doesn't gives any advantadge as such. The advantadge comes from having a model that fits very nicely with the specific set of problems that you are trying to solve in that context

#### A Strategic Design Decision

An example: allow front-end team to get a list of all vehicles in order to represent them as a search result.

- Refactor

- New subsystem

- Force the new functionality into the existing model