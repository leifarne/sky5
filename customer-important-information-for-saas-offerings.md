# Important information for SaaS offerings

When procuring SaaS solutions where the hosting of the application is done via a third party IaaS/PaaS cloud offering
(such as AWS, GCP or Azure) it is very important to understand whether your SaaS agreement has the consequence that the
“hosting part” of the SaaS offering is delivered as part of the SaaS agreement or whether a separate agreement will be
considered established between you and the third party IaaS/PaaS cloud supplier.

Why is this important?

If your SaaS provider has contracted with Azure, AWS or GCP in such a way that you do not need to accept the customer
agreement/cloud terms from either Azure, AWS or GCP and thus enter into a direct agreement with the applicable cloud
provider, this means that you as a starting point only have to relate to your SaaS suppliers terms and conditions. Not
having to accept Microsoft Customer Agreement or Amazon Customer agreement etc may seem appealing, as it will save you
“time and trouble” of having to read such terms and conditions and adhere to it. E.g. it may seem as a way to simplify
the end-customers contract process.

However, in order for your SaaS provider to be allowed to use either Azure, AWS or GCP as its hosting platform when
providing its SaaS offering to end customers like you, the SaaS provider need its own agreement which will authorize it
to resell Azure, AWS or GCP as part of its SaaS offering, and it will normally be *“responsible for that end customers
use are in accordance with the terms and conditions”* applicable to the SaaS provider.

This has the following (not so obvious) consequences for you:

- If you or any other end customer of the SaaS provider breaches (for instance Acceptable Use Policy, Export control or
Use Restrictions) the agreement between Azure, AWS or CCP and your SaaS provider, this will be considered a breach by
your SaaS provider towards the applicable third party IaaS/PaaS cloud provider, and such cloud provider will normally be
entitled to suspend and/or terminate the IaaS/PaaS-services towards your SaaS provider, and all of the other SaaS
provider end customers including yourself. E.g one end customer’s failure **may affect** you and all other 999 customers.
This means that this agreement model give a high risk from your end customer perspective, which you should assess
carefully. For instance, if the SaaS solution is business critical for you, and the availability of the SaaS service
rely on both your SaaS provider and all other end customers being compliant with the applicable cloud providers terms
and conditions, you should assess whether you can take this risk.

Our recommendation is to at least ask your SaaS provider about possible mitigating actions taken in order to reduce the
risk for such a situation. As the larges risk for breach of Azure, AWS and GCP terms and conditions, is breach of for
instance the **Acceptable Use Policy** (which normally have prohibitions against illegal content, using the cloud services
for illegal purposed, to spam and distribute malware etc), the **Use Restrictions** (don’t reengineer, work around technical
limitations, impair the cloud suppliers IPR or share the online services with third parties etc), or the **Export Control
regulations**, we recommend the following questions:

- Export control: ask your SaaS supplier how they ensure that other end customers do not breach such regulations, are
there for instance technical measures that will prevent use in countries which are on an embargo list?

- Use restrictions; is the SaaS offering designed so that end customers have no possibility to reverse engineer the cloud
supplier IaaS/PaaS services (LEIF ARNE; litt usikker på om dette er praktisk mulig uansett, fint om du supplerer her),
ensure that other end customers cannot share its SaaS offering with third parties that does not use it only for the
purpose of the applicable end customers business purpose, and include normal security measures to prevent unauthorised
access?  (føler dette ble litt for selvfølgelig og lite relevant, tenk litt her L/A)

- Acceptable Use Policy, in order to prevent end customers storing illegal content in Azure, content that infringes third
party rights, using the online services for illegal purposed, to spam and distribute malware etc, is the solution
designed so it’s not possible to do the above?

- Without a direct agreement with the third party IaaS/PaaS cloud provider, you do not get any protection from that cloud
provider for infringement claims from third parties. For instance, only the “Customer” (your SaaS provider) is protected
under the MS Customer Agreement “against third party claims”, not “third parties” if sued directly such as you as an end
customers. Your SaaS provider may offer this in its owns terms and conditions, but often we see that third party
services are excluded. This should be checked carefully.  That the end-customer gets no protection from Microsoft in
case third party infringement claims.

- Without an direct agreement with the third party IaaS/PaaS cloud provider, no data processor agreement will be
established between you and the applicable third party IaaS/PaaS cloud provider, nor will you get protection under the
Standard Contractual Clauses (SCC). Since Azure, AWS and GCP may use service technicians outside EU, this means that
you as an end customer probably not will be compliant under the data protection legislation (if this happens)
since you will not have a direct SCC with Azure, AWS or GCP which is needed when SCC are used.

Mitigations to consider: You should check whether the Azure, AWS and GCP services used to offer your SaaS offering in
fact depend on either storage of data outside of EU, or use of service technicians outside of EU. If so, you should ask
your SaaS provider whether it has negotiated special terms with its cloud provider, establishing a form of direct SCC
towards you as an end customer after all. The new draft for SCC from the Commission however, have a fix that makes this
problem go away, if approved as is. This will hopefully happen this fall.

- Without an direct agreement with the third party IaaS/PaaS cloud provider, you as an end Customers get no protection for
any claims/fines due to breach of the privacy act from the third party IaaS/PaaS provider. You should assess whether
your SaaS provider offers this protection after all.

In order to avoid the above-mentioned risks, there is always the possibility to require that your SaaS provider enters
into a resale model with either Azure, AWS or GCP, which has the effect that you as an end customer needs to accept the
terms and conditions of either Azure, AWS or GCP as applicable, and a direct agreement is created between you and Azure,
AWS or GCP as applicable.

We assume that the reason why so many SaaS providers in the market use the hosting exception instead of becoming a CSP,
is that under the “hosting exception” the Azure tenant will belong to the SaaS provider, and the end customers will not
have one tenant each (multi tenant). Then it is easier to establish a multitenant solution, keeping cost down when mass
distributing updates to all end customers at once.