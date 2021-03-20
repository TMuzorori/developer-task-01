Cassava developer task 01, issues log.

econet-utils/ MobileNumberUtils
issue1 =>compilation error cause by non static logger
solution=> declare logger as a static final

electronic-payments-domain
Subscriber request
issue2=> @PreInsert do not exist in hibernate persistance

Solution
* Use @PrePersist, that’s the right annotation

electronic-payments-business
PartnerCodeValidatorImpl
issue3=> error calling the super constructor

*solution correct the error by calling the constructor without puting it inside a this()
PartnerCodeValidatorImpl
issue3=> compilation error, use of persist to save subscriberRequest, a method not available in the subscriberRequestDao

*solution => use save
