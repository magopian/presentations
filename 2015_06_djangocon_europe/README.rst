Switching from nose to py.test at Mozilla
=========================================

Talk for `Djangocon Europe 2015 <http://2015.djangocon.eu/talks/>`_.

py.test is a test runner similar to the more popular nose. Over the last years,
py.test has gained traction, is still very actively maintained, and has many
very attractive features.

We will first discuss why would someone use py.test over nose, quickly recap
how to write tests in py.test (and see that it's more pythonic), then see how
to switch a large codebase with many existing tests to using py.test (spoiler:
it's easy).

py.test is in my opinion (and in many other people's opinions too, including
some Django core devs) superior to nose. As it's not as popular (yet!), and as
Django usually takes advantage of nose-like features, people don't know it as
well, or are afraid to switch, thinking they would need to rewrite all their
tests.
We'll also see how it can easily integrate with travis and tox, and ease the
splitting of builds on travis for faster runs on slow builds.
