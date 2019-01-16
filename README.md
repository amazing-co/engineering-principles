# ac-engineering-principles

AmazingCo Engineering Principles

## Be a Technology Agnostic

Pick the best tool for the project
from technology as the blocker to IT as the enabler
Embrace innovations, trials and error with new technology
Unix over windows
platform agnostic techstack vs platform specific
cloud agnostic

## Metrics is KING

As part of Build, Measure, Learn
Capture & Log everything so that we have visibility

## Automation For The Win

Separate Code from Infrastructure
When everything goes down, we just need to spin up new infrastructure, no CI is needed

## Design for Failure

You know the system will fail,
Fail faster and fail noisily but make sure the system knows what to do when it fails

## Prefer Messaging Queue over API call

Presentation -> API -> SNS -> SQS -> Worker -> Another API -> DB
is better than
Presentation -> API -> DB

- Fire and Forget, Asyncronous
- Replay Mechanism
- Failure Safe
- Scalable

## Compile Time Dependencies are preffered more than Run Time Dependencies

No Surprises!

## Go Live on "Day One"

The hardest part in the microservices / SOA these days are so many little components and connecting the dots would be the biggest challange
- Infrastructure
- Network: Route53, CloudFront, ELB, VPC, EC2, Container
- Security: SG, IAM
- Latency
- Replication
- Cost

## Interface first

- Contract Driven

## Cloud First

## Mobile First

## Offline First

## Container First

## [12 factor](https://12factor.net/)

### Codebase

One codebase tracked in revision control, many deploys

### Dependencies

Explicitly declare and isolate dependencies

### Config

Store config in the environment

### Backing services

Treat backing services as attached resources

### Build, release, run

Strictly separate build and run stages

### Processes

Execute the app as one or more stateless processes

### Port binding

Export services via port binding

### Concurrency

Scale out via the process model

### Disposability

Maximize robustness with fast startup and graceful shutdown

### Dev/prod parity

Keep development, staging, and production as similar as possible

### Logs

Treat logs as event streams

### Admin processes

Run admin/management tasks as one-off processes

## Unix Rules/Principles

### Rule of Modularity

Write simple parts connected by clean interfaces.

### Rule of Clarity

Clarity is better than cleverness
Consistency is better than "Best-Practice"

### Rule of Composition

Design programs to be connected with other programs.

### Rule of Separation

Separate policy from mechanism; separate interfaces from engines.

### Rule of Simplicity

Design for simplicity; add complexity only where you must.
A Bit of Copy and Pasting is Better than Over Complicated Things in the Beginning

### Rule of Parsimony

Write a big program only when it is clear by demonstration that nothing else will do.

### Rule of Transparency

Design for visibility to make inspection and debugging easier.

### Rule of Robustness

Robustness is the child of transparency and simplicity.

### Rule of Representation

Fold knowledge into data, so program logic can be stupid and robust.

### Rule of Least Surprise

In interface design, always do the least surprising thing.

### Rule of Silence

When a program has nothing surprising to say, it should say nothing.

### Rule of Repair

Repair what you can — but when you must fail, fail noisily and as soon as possible.

### Rule of Economy

Programmer time is expensive; conserve it in preference to machine time.

### Rule of Generation

Avoid hand-hacking; write programs to write programs when you can.

### Rule of Optimization

Prototype before polishing. Get it working before you optimize it.

### Rule of Diversity

Distrust all claims for one true way.

### Rule of Extensibility

Design for the future, because it will be here sooner than you think.
