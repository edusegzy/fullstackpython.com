title: Redis Queue (RQ)
category: page
slug: redis-queue-rq
sortorder: 0431
toc: False
sidebartitle: Redis Queue (RQ)
meta: Redis Queue (RQ) is a Python task queue built on top of Redis that executes work outside an HTTP request-response cycle.


# Redis Queue (RQ)
[Redis Queue (RQ)](http://python-rq.org/) is a Python
[task queue](/task-queues.html) implementation that uses Redis to keep
track of tasks in the queue that need to be executed.

<a href="http://python-rq.org/" style="border: none;"><img src="/img/logos/redis-queue.png" width="100%" alt="Redis Queue (RQ) task queue Python project logo." style="border-radius: 5px;" width="100%" class="technical-diagram"></a>

<div class="well see-also">RQ is an implementation of the <a href="/task-queues.html">task queue</a> concept. Learn more in the <a href="/web-development.html">web development</a> chapter or view the <a href="/table-of-contents.html">table of contents</a> for all topics.</div>


## RQ resources
* The [RQ intro post](http://nvie.com/posts/introducing-rq/) contains
  information on design decisions and how to use RQ in your projects.

* [International Space Station notifications with Python and Redis Queue (RQ)](https://www.twilio.com/blog/2015/11/international-space-station-notifications-with-python-redis-queue-and-twilio-copilot.html)
  shows how to combine the RQ task queue library with Flask to send
  text message notifications every time a condition is met - in this blog
  post's case that the ISS is currently flying over your location on
  Earth.

* [Asynchronous Tasks with Flask and Redis Queue](https://testdriven.io/asynchronous-tasks-with-flask-and-redis-queue)
  looks at how to configure RQ to handle long-running tasks in a Flask app.

* [Flask by Example - Implementing a Redis Task Queue](https://realpython.com/blog/python/flask-by-example-implementing-a-redis-task-queue/)
  explains how to install and use RQ in a [Flask](/flask.html) application.

* [rq-dashboard](https://github.com/eoranged/rq-dashboard) is an awesome
  [Flask](/flask.html)-based dashboard for viewing queues, workers and
  other critical information when using RQ.

* [Sending Confirmation Emails with Flask, Redis Queue, and Amazon SES](https://testdriven.io/sending-confirmation-emails-with-flask-rq-and-ses)
  shows how RQ fits into a real-world application that uses many
  libraries and third party APIs.
