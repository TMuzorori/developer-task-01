Cassava developer task 01, issues log.

econet-utils/ MobileNumberUtils
issue1 =>compilation error cause by non static logger
solution=> declare logger as a static final

electronic-payments-domain
Subscriber request
issue2 @PreInsert do not exist

Solution
* Use @PrePersist, that’s the right annotation