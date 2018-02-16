# Personal Information Management services
This is a repository to manage strategy around a small organisation's PIM services. Because we always forget how we were supposed to configure the thing.

The specific need for this is about how the big software in the cloud providers always have an interest in setting up your DNS to favour their ecosystems, when often, you're looking for a cross-ecosystem solution. 

In our case, it's about being able to use all kinds of services with all kinds of systems, but having them all link to the same identity. (i.e. one can gChat to the same identity as Skype, one can share an Office 365 document to the same identity as a GoogleDoc, and particularly, they all stay GDPR compliant.)

# Considerations
## Data handling
How do you make sure your Office instance doesn't access your google instance? You don't want Office stuff to end up being synced to a different region.

## Multi-region
What if you had interest in working in China, US, UK, Canada, Russia? Where is the data stored?

## Naming
### Naming for users
Outbound, you always want to be firstname.lastname@domain.com. Inbound, you want the same. Publicly, it's agnostic. Internally, you want to use the same. 

### Naming for administrators
Best to use admin@domain.com? Or to use an individual's identity?



# It's an interesting challenge.
