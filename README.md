<p align="center">
    <img src="https://media.github.ibm.com/user/376942/files/7bb5fe80-231a-11ed-8440-8c14e1e3c289" height="160">
    <h1 align="center">Airflow DAG Analytics</h1>
</p>

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://media.github.ibm.com/user/376942/files/8a535880-27e7-11ed-8340-edc7b6f1a231)](https://airflow.apache.org/)


<br>

<h2><img height="20" src="https://media.github.ibm.com/user/376942/files/ebc48480-231a-11ed-8b70-30e2b8893504">&nbsp;&nbsp;What is ADA?</h2>

ADA is a microservice with the main purpose to retrieve key analytics metrics for task and dag level from your Airflow database instance.


<h2>Contents</h2>

- [Business context](#business-context)
- [Deployment](#deployment)
	- [Code Engine tutorial](#code-engine-tutorial)
- [Engine compatibility](#engine-compatibility)

<h2>Business context</h2>

The amount of stuck pods became an increasing pain for us: whenever they happened, they would demand support requests followed by analysis that often resulted in simple and manual actions. Based on that, there arose a need to automate this process, in other words, to make us able to identify a stuck pod and take the appropriate action in a fully automatic way, transparent for both developer and user.

Well, but what is the best way to identify a stuck pod? The answer is simple: based on historical data, we can tell if something is taking longer than it should to run. That’s when the perfect opportunity arose to implement, for the first time, a **Serverless computing module**.

<h2>Deployment</h2>

<h3>Code Engine tutorial</h3>

For more information, access https://cloud.ibm.com/docs/codeengine.

<h2>Engine compatibility</h2>