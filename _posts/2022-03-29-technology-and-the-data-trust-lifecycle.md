---
layout: post
title: Technology and the data trust lifecycle
author:
- family: Ainsworth
  given: John
  institute: University of Manchester
  person_page: john-ainsworth
featured_image: /assets/images/the-data-trust-lifecycle.png
excerpt: With both our understanding of how to operationalise data trusts and our technical capabilities changing at pace, part of the challenge today is to really pin down how the technologies we have map onto the functions that data trusts need to deliver. 
date: 2022-03-29
redirect_from:
  - /blogs/technology-and-the-data-trust-lifecycle
  - /blogs/technology-and-the-data-trust-lifecycle/
---

*Following our recent seminar on the* [*Technologies behind data
trusts*](https://youtu.be/ol3kY1NhEjE)*, Professor John Ainsworth,
University of Manchester, explores the data trust lifecycle and
identifies what questions practitioners should ask when developing their
technology strategy.*

We know that technology has an important part to play in helping
create data trusts, but what does that mean in practice? With both our
understanding of how to operationalise data trusts and our technical
capabilities changing at pace, part of the challenge today is to
really pin down how the technologies we have map onto the functions
that data trusts need to deliver. 

Data trusts vary in their nature – their purpose, focus, and
stakeholders – and in their data strategies. While the focus of data
trusts is management of the rights associated with data, the different
types of data that trusts interact with and how these different data
types are structured will affect their data management strategy. These
differences affect how practitioners can go about building and
maintaining a data trust, and the technologies that might be useful
for them. However, looking across the lifecycle of a data trust, we
can draw some lessons about what types of technology are useful, and
what questions practitioners should ask when developing their
technology strategy.

We can think about five stages of the data trust lifecycle: recruiting
and enrolling members; populating the trust with data; making data
accessible; maintaining trust; and sustainability.


![The Data Trust Lifecycle, John Ainsworth, University of
Manchester](/assets/images/the-data-trust-lifecycle.png)

To start, we need to think about who is part of the data trust, and
where the data for the trust is coming from. Here, there are
fundamental questions about why people should engage with a data
trust. Usually, people or organisations are looking for some type of
value to be created by the trust, by changing how their data is
managed or used. That value can take many different forms, but –
unless all participants in the trust are engaging altruistically – at
its core a data trust will need a mechanism for returning value to its
members. Practitioners will need to understand what type of value is
meaningful to the members of their trust: this could be money; better
services; influence, control or certainty around data use; tokens; or
some other reward. The form of value that the trust is trying to
create will influence the technologies it will need.

There is also a technical element to managing *member recruitment* or
enrolment. Data trusts are often driven by an interest in serving a
particular community, so those managing a trust need to think about
how to link the technologies being used to the interests and dynamics
of that community, and to community-building efforts.

Secondly, practitioners need to think about *how to populate a data
trust with data*: where is data coming from, and how will it get
‘into’ the trust? Answers to these questions will again vary with
context. For example, in healthcare, a lot of the data we’re
interested in comes from health records. We can’t easily move those
around between organisations or systems; they need to stay in one
place. That means we need to think about how we access the information
they hold – and use this data alongside other information sources –
without bringing everything together in one place.

Again, these questions point to a foundational decision in setting up
a data trust: will the trust be involved in the business of managing
data itself, or will it be managing access to data? The choice of
operating model here will affect the trust’s technical architecture:
does it need to bring data together, will a federated structure work,
or does the trust create space to bring users to the data? In
healthcare, we frequently use trusted research environments or secure
facilities where researchers can access sensitive data, without
holding that data themselves.

Broadly-speaking, those setting up a trust will have two technology
options when thinking about populating the trust with data. If data is
moveable, then centralising it (creating one giant data repository)
might be possible; if data needs to remain under the control of the
organisation or individual that currently holds it, then a federated
data infrastructure will be necessary. Across both of these options,
practitioners will need to grapple with the technicalities of data
harmonisation. When trying to bring data into the trust, we need to
think about whether the different data sources being brought together
are in the same format, or whether further work is needed to make
sense of it.

The third stage in the lifecycle is about *making data accessible*. An
objective of many data trusts is to increase data use, creating value
through that use. Technical interventions may be necessary to achieve
that goal. For example, to make data accessible to external
organisations or parties that might want to use it, there will need to
be descriptions of what data the trust manages, with what access
conditions, and in what formats. This requires metadata descriptions.

In the next stage of the trust’s lifecycle, those managing a trust
need to think about how they will keep contributors engaged and
confident in the trust’s operations – essentially *how the trust will
maintain trust*. There are various aspects to ‘trust’ that will be
important, and different technologies can be useful in creating a
system that delivers on those different aspects. Privacy preserving
technologies can help manage concerns about what types of insight can
be derived from data, and to demonstrate compliance with policy or
regulatory requirements around personal data; immutable audit trails
might be needed to prove who has accessed what data, and with whose
approval, and distributed ledger technologies can help provide these;
transparency is also an important element of trust – can the data
trust demonstrate it has acted in accordance with its commitments –
and technical systems will need to be designed for such transparency.

Last, but by no means least, is *sustainability*. Creating a data
trust is all very well, but what is the model that will sustain it?
From where will revenue come to support a potentially complex
technical infrastructure and the people needed to maintain and operate
that infrastructure? This also relates to the questions at the start
of this post about value: who is expecting to receive what type of
value from the trust, and how will the trust return that value to
them?

In our Civic Data Identity Platform project, we’ve been working
through some of these questions in the context of health data. We’ve
been particularly interested in blockchain as an underlying technology
that allows you to deal with the process of signing up, recruiting,
and returning value to people. These technologies allow us to analyse
how information and revenue flows across the data trust value chain,
and how that affects the services that can be provided to members.


Through this work, and building on discussions from the Data Trusts
Initiative, we can start to see *a checklist of questions that data
trust practitioners can use to develop their technology strategy:*

* What type of value is the trust creating and for who?

* How will members of the trust be recruited? What technical system
is needed to enrol new members and manage their information?

* Where is the data of interest to the trust currently held?

* Is the trust holding data itself or managing data access? How
does this affect the value it seeks to create?

* How will data get ‘into’ the trust? Will it be held by other
organisations, and accessed by the trust, or held centrally by the
trust?

* Is the data being brought together in the same format, or is
further work needed to curate it?

* What do the trust’s users expect? How will the trust maintain
trustworthiness?

We’ll be launching the full results of our work with the Civic Data
Identity Project on 28 March. You can find out more
[here](http://cdip.lancs.ac.uk), and read more about the Data Trusts
Initiative’s
[emerging operational framework for data trusts here](https://datatrusts.uk/blogs/creating-a-pathway-to-successful-real-world-data-trusts).

