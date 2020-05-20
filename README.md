# Event Driven Architecture Workshop 

## About OSO DevOps

We are a DevOps and Amazon Web Services (AWS) Professional Services
Consultancy based in London. We build secure bespoke automated big data
platforms on AWS using open source tooling, helping businesses to
extract value from their data in the most cost effective and agile way.
We provide self service tooling to enable business workflows to make
data driven decisions.

## Our Approach To The Workshop

To help you understand and harness the power of event driven
architectures, we propose to deliver a 2 day workshop to cover the
architecture, data model and roadmap for the secure deployment of Kafka.
The workshop is not purely a technical exercise. It will cover people
and process aspects of how Kafka can be consumed at scale throughout the
organisation. Documentation is a large part of the workshop and will be
delivered after the engagement.

Following the workshop, recommendations will be provided, adding depth
to the findings where requested by senior stakeholders. By applying OSO
DevOps proven agile methodology, the overall risk will be reduced to a
clear set of deliverables, drawing on our high performing team of
experts.

## Agenda:

<table>
<thead>
<tr class="header">
<th colspan="3"><strong>Day 1 </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="14%"><strong>Time</strong></td>
<td width="56%"><strong>Topic</strong></td>
<td width="30%"><strong>Output</strong></td>
</tr>
<tr class="even">
<td>09:30 - 10:00</td>
<td><strong>Introduction to Apache Kafka and event-driven architectures.</strong></td>
<td></td>
</tr>
<tr class="odd">
<td>10:00 - 12:00</td>
<td><p><strong>Capture current architecture practices, standards:</strong></p>
<ul>
<li><p>Stakeholders and their requirements</p></li>
<li><p>FOSS v Commercial v Cloud</p></li>
<li><p>Strawman architecture of client ecosystem (including: choreography / orchestration/workflows)</p></li>
<li><p>Technology stack (frameworks, data formats)</p></li>
<li><p>Development processes (source repo, build pipelines, automation, self-service)</p></li>
<li><p>Regulations / compliance / reporting (PCI, GDPR, etc)</p></li>
<li><p>Security standards and architecture / implementation (LDAP, OAuth, SSO, Vault etc)</p></li>
<li><p>Tooling (alerting / monitoring / logging / orchestration)</p></li>
<li><p>DevOps, operations, practices tooling WRT: run-books, No-ops, infra-as-code upgrades, 24x7, uptime, release processes &amp; support processes.</p></li>
<li><p>Infrastructure (cloud provider / DC / regions / OS)</p></li>
<li><p>Future direction and timeline</p></li>
</ul></td>
<td>Captured line items, weighted in terms of relevance to following activities. A list of assumptions together with priorities and timeframes.</td>
</tr>
<tr class="even">
<td>12:00 - 12:45</td>
<td><strong>Lunch break.</strong></td>
<td></td>
</tr>
<tr class="odd">
<td>12:45 - 15:00</td>
<td><p><strong>Enumerate Kafka ecosystems pros / cons and features required. </strong></p>
<ul>
<li><p>Detailed explanation of schema-registry, replication options MM2 v replicator, data-balancing, over-partitioning, retention, transactionality, REST proxy, security options.</p>
</li>
<li><p>SWOT Confluent enterprise, community &amp; cloud features.</p>
</li>
<li>
<p>SWOT AWS MSK, Kafka OSS &amp; complementary tools (monitoring, alerting, management)</p>
</li>
<li>
<p>Score SWOT outputs on factors including (L/M/H)</p>
<ol type="1">
<li>
<p>Suitability for dev and/or prod</p>
</li>
<li>
<p>Cost</p>
</li>
<li>
<p>Security and encryption</p>
</li>
<li>
<p>Support (i.e. skills and tooling for self-support vs cloud support etc)</p>
</li>
<li>
<p>Operations</p>
</li>
<li>
<p>Current business appetite</p>
</li>
<li>
<p>Fit strategic direction (i.e. cloud, central-nervous-system, security, hybrid cloud, multi-cloud)</p>
</li>
</ol>
</li>
</ul>
</td>
<td>Capture scoring and the qualified recommended solution (and gaps) for production and pre-prod. Implement a high level plan proposal / steps / timelines with dependency tracking.</td>
</tr>
<tr class="even">
<td>15:00 - 15:30</td>
<td><strong>Break.</strong></td>
<td></td>
</tr>
<tr class="odd">
<td>15:30 - 16:30</td>
<td><p><strong>Identify high level requirements:</strong></p>
<ul>
<li>
<p>Service availability, regions and SLA commitments.</p>
</li>
<li>
<p>Current production runbooks / deployment pipelines.</p>
</li>
<li>
<p>Development / testing environment requirements.</p>
</li>
<li>
<p>CI / CD tooling requirements.</p>
</li>
<li>
<p>Key management and certificate requirements.</p>
</li>
<li>
<p>Data classification and schematic versioning</p>
</li>
</ul></td>
<td>High level strawman deployment architecture for all none-production and production environments</td>
</tr>
</tbody>
</table>

<table width="100%">
<thead>
<tr class="header">
<th colspan="3"><strong>Day 2 </strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td width="14%"><strong>Time</strong></td>
<td width="50%"><strong>Topic</strong></td>
<td width="40%"><strong>Output</strong></td>
</tr>
<tr class="even">
<td>09:30 - 10:00</td>
<td><strong>Review of Day 1, the outputs and assumptions captured.</strong></td>
<td></td>
</tr>
<tr class="odd">
<td>10:00 - 10:30</td>
<td><p><strong>Educational session on Kafka in production:</strong></p>
<ul>
<li>
<p>Key architectural principles to adhere to.</p>
</li>
<li>
<p>A blueprint of common architectural patterns.</p>
</li>
<li>
<p>How to scale Kafka in production.</p>
</li>
<li>
<p>Concepts of Kafka Connect.</p>
</li>
<li>
<p>KSQL vs Kafka Streams.</p>
</li>
<li>
<p>Self service tooling and Kafka ecosystem of connectors.</p>
</li>
</ul></td>
<td></td>
</tr>
<tr class="even">
<td>10:30 - 11:00</td>
<td><p><strong>Education session on DevOps in distributed architecture:</strong></p>
<ul>
<li>
<p>How to build and deploy high performance, fault tolerant systems.</p>
</li>
<li>
<p>How to measuring DevOps success with four key metrics:</p>
<ol type="1">
<li>
<p>Lead time for changes</p>
</li>
<li>
<p>Deployment frequency</p>
</li>
<li>
<p>Time to restore service</p>
</li>
<li>
<p>Change failure rate</p>
</li>
</ol>
</li>
</ul>
<ul>
<li>
<p>DevOps tooling (automation / monitoring / alerting / reporting / metrics.</p>
</li>
<li>
<p>DevOps tooling.</p>
</li>
</ul></td>
<td></td>
</tr>
<tr class="odd">
<td>11:00 - 12:00</td>
<td><p><strong>Capture operational infrastructure and processes: </strong></p>
<ul>
<li>
<p>Monitoring tools and metrics (incl self hosted and others).</p>
</li>
<li>
<p>Discuss monitoring / alerting options.</p>
</li>
<li>
<p>How to handle dead-letter queues.</p>
</li>
<li>
<p>Audit processes.</p>
</li>
<li>
<p>Logging and log retention policy.</p>
</li>
<li>
<p>Support and out of hours issue resolution</p>
</li>
<li>
<p>Patching and vulnerability scanning.</p>
</li>
</ul></td>
<td><p>Map onto the recommended Kafka ecosystem. Recommended operational tooling</p>
<p>implementation plan proposal / steps / timeline.</p></td>
</tr>
<tr class="even">
<td>12:00 - 12:45</td>
<td><strong>Lunch break.</strong></td>
<td></td>
</tr>
<tr class="odd">
<td>12:45 - 13:15</td>
<td><p><strong>Identify and scoping development requirements:</strong></p>
<ul>
<li>
<p>Development environment, developer onboarding and tooling requirements.</p>
</li>
<li>
<p>Source control policy and tooling.</p>
</li>
<li>
<p>CI / CD deployment and pipelines.</p>
</li>
<li>
<p>Cost analysis on anything new.</p>
</li>
<li>
<p>Skills matrix of existing development team.</p>
</li>
</ul></td>
<td>Strawman development architecture and tooling. Recommended operational tooling &amp; implementation plan proposal / steps / timeline.</td>
</tr>
<tr class="even">
<td>13:15 - 15:45</td>
<td><p><strong>Use case modeling:</strong></p>
<ul>
<li>
<p>Capture the first use-case as a dataflow including key distribution, partition assignment, data flow points, cost of failure, choreography.</p>
</li>
<li>
<p>Data model and evolution including serialization format / compatibility / evolution.</p>
</li>
<li>
<p>Validate requirements (correctness, side effects).</p>
</li>
<li>
<p>Upgrade paths and strategy.</p>
</li>
<li>
<p>Future / envisaged use-case states.</p>
</li>
<li>
<p>Workload characteristics (historic, test, live, etc) with respect to:</p>
<ol type="1">
<li>
<p>Throughput.</p>
</li>
<li>
<p>Latency</p>
</li>
<li>
<p>Volume</p>
</li>
<li>
<p>Retention</p>
</li>
<li>
Resilience
</li>
</ol></li>
</ul>
</td>
<td><p>Capture and document findings.</p>
<p>Provide high-level data-flow model. Recommended deployment and implementation plan proposal / steps / timeline for testing and productionisation.</p></td>
</tr>
<tr class="odd">
<td>15:45 - 16:00</td>
<td><strong>Break.</strong></td>
<td></td>
</tr>
<tr class="even">
<td>16:00 - 17:00</td>
<td><p><strong>Initial planning activity dependency mapping and feedback:</strong></p>
<ul>
<li>
<p>High level statements of work.</p>
</li>
<li>
<p>Roadmap of dependencies.</p>
</li>
<li>
<p>Next steps.</p>
</li>
<li>
<p>Session feedback.</p>
</li>
</ul></td>
<td>Dependency flow of activities broken down as work package activities</td>
</tr>
</tbody>
</table>

## Resourcing and Logistics

OSO DevOps can typically initiate a full workshop team within 1-2 weeks,
but can often mobilise teams faster. [OSO DevOps](https://osodevops.io/) will select the
following resources for this project:

**Neil Avery** has over 25 years of commercial software development.
Recently he worked at the Office of the CTO within Confluent to help
shape the future direction of Kafka and Streaming in general. He has
been instrumental in developing KSQL and Kafka Streams as well as
helping large organisations understand how Kafka is adopted at scale.
His blog series [Journey to event driven](https://www.confluent.io/blog/journey-to-event-driven-part-1-why-event-first-thinking-changes-everything/)
has helped shape mindset and understanding of what Kafka adoption means.
Recently, authoring the Kafka Transport binding for CloudEvents 1.0 and
also has a keen interest in Cloud, serverless and the next generation of
technology (quarkus).

**Sion Smith** has over 18 years of commercial software development
experience and twelve years experience with Java and the Spring
Framework. His focus and experience are predominantly in the financial
services sector, gaining expert knowledge of the Spring Boot and Kafka
framework. Experienced in event-driven programming principles, using a
mixture of open source and Confluent Kafka.
