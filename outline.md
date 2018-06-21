Three high-level sections:

(35 minutes)

1. Demystifying automation
    a. Heinous automation lies
        i. wrap up with "automation doesn't exist" bomb
    b. Why reliability is what this has always been about
    c. The Automation "Last Mile" (a.k.a. the 80/20 rule). 
        i. Gotta be a composer. Need to have good instruments but you also have to know how to use them. Need both.
        ii. Assemble things that do one job and do it well.
        iii. THIS is where the automation focus should be
2. NRE Use Cases - for **each** please say how these things HELP reliability.
    a. Automated Testing
        i. Neteng tests (unit tests)
        ii. Traffic Tests - Ixia/Spirent/ToDD/jmeter - traffic stuff, gotta augment with assertions, and tie it into the pipeline. Not just about performance, focus on tying back up to SLI. Caring about end-user experience is the best. We can all have our specialties (routing, security, etc) but it all has to align to the outcome.
        iii. Predictive testing - Include forward networks and veriflow and figure out where they fit. You don't want to omit that area of testing and have them respond saying you're outdated. Need to be thinking of all the new types of testing, as well as the "old".
        iv. Chaos testing (talk about problem surface briefly and set up for long-form chaos engineering post later on)
    b. Event-Driven
        i. Signals and Events
        ii. Rules
        iii. Workflows - decisions
        iv. Actions/Outputs - work
    c. Infrastructure as Code (config mgmt is a component of this, sure, but far from the whole thing.)
        i. I'm like the SDN stalwarts....I don't just mean "code". I am the IaC hipster.
        ii. It’s not like we started doing quantum physics - it was a better spin on the same thing we were already doing.
        iii. Git is the new interface. Why? Because the path is auditable, and visible. Clicky clicky, typy typy is not.
        iv. Give ebay webserver example.
        v. Maybe Chatops is next? or VRops? Or MATRIX OPS WTF
        vi. Demystifying automation. Why a focus on network operations automation has always been the point. Why automation and iac isn't that special, they're really just "modern ops" - stop doing CLI and GUI clicking. Antecdote about st2 AWS from hand-made servers to terraform. It’s not like we started doing quantum physics - it was a saner spin on the same thing we were already doing.
3. How can I get started?
    a. Understand and document workflows END TO END. Talk about SFO ticketing example. Actively work to reduce tribal knowledge.
    b. Start thinking about opportunities to increase reliability, and HOW you're measuring progress here. Track operations growth, MTBF and MTTR, and how existing metrics feed up into SLI.
    c. Feed reliability metrics back into your operations, so that when reliability increases, you know to keep going. When its flat or drops, you know you have something to take a closer look at.


# Demos

## Testing

- ToDD
- jsnapy

## EDI

- syslog and tickets (David)

## Infra as Code

- template and yaml data file, push to device. User doesn+'t interact with device, only with git
