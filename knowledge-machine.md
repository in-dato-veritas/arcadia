*Arcadia should be built on top of four key modules: Data Warehouse, Knowledge Machine, Digital Profile and Underlying Economics. The Knowledge Machine allows all the participants to work together in order build knowledge on top of quality data previously uploaded by the users.*

# Purpose

The Knowledge Machine establishes **a way for users and developers to collaborate together** so that raw data from the users are converted into knowledge usable by other users and companies. There exist **built-in incentives** for user to upload data and for developers to extract value from it. In doing so, Arcadia's core values of trust, privacy and control must be remain enforced at all time. Therefore, their must exist a way for users to **share their data with developers** without revealing information about themselves, and for developers to **share their algorithms with everyone** without loosing their intellectual property rights. The Knowledge Machine should also **produce outputs that have consistent meaning** for every users so that they can be used in different contexts without being prone to misunderstanding or manipulation. To improve upon algorithms that produce the outputs of the Knowledge Machine, ground truths should be used extensively. **Mechanisms to establish the ground truth and compare different algorithms** will therefore be required.

# Incentives for building the digital profile

If there is no incentives to upload data and no incentives to extract value from it, we can expect zero work to be done. As not everyone react to the same thing, incentives should be of various natures. There should be **reciprocal dependencies**, **economic incentives** and **reputation incentives**.

## Reciprocal dependencies

* Make it so that what users can hope to get from their data depends on what other users get. Their can exist some elasticity, but generally, one user should get more because all the users get more.
* Users alone won't be able to get value form their data. Developers on the other hand need data and won't be able to do it without the collaboration of the users.
* Algorithms from one developer can be used within the algorithm of another developer.

## Economic incentives

* To avoid spamming, when uploading new data to Arcadia, the user is asked to do a small deposit. After a **validation process** has successfully terminated, the deposit is returned. If the data is declared bad or suspicious, the deposit is burned or is distributed amongst all the users. The deposit could be worth what the validation process costs.
* For the same reason, when uploading a new algorithm to Arcadia, the developer is asked to do a small deposit.
* For a certain period of time, if the characteristics of a user are used more, he will earn more. But if the same user doesn't update his data or stop using Arcadia, then he will earn less or stop earning completely.
* The algorithms that are used in services for which clients will pay give the developer **rights to earn royalties**.
* To develop a new algorithm, a developer can ask for the help of some users. In this case, both the developer and the users who collaborate have rights to claim royalties when the algorithm is used.

## Reputation

* Users who upload bad data will see their `reputation score` decrease, up to a point where they might be excluded from some services. This means they could potentially stop earning for the use of their profile.
* Users can vote on an algorithm submitted by a developer and by doing do, express how good (or bad) it reflects their personality.
* Developers can affect users' `reputation score` if they detect problems in the data they upload.
* Clients can vote on the service they paid for, therefore affecting companies' `reputation score`.
* Special `reputation points` can be earned when e.g participating as volunteers in academic projects.

# Working with personal data

* Avoid spamming from developers: use small `deposits` from uploading.
* Users can share their data without revealing information about themselves
* Developers can share their algorithms with everyone without loosing their intellectual property rights
* A digital profile representative of a generic user, based on all the data available in Arcadia could be used in order to let developers work with real data but without being able to identity any user in particular.

# Characteristics as building blocks

Developers extract knowledge from the data uploaded by the user. The results or the interpretation that is obtained is called a **characteristic**:

> Characteristics are irreducible elements that cannot be explained in more fundamental terms unless accessing the data itself.

Characteristics are elements with a one level of abstraction from the data (i.e variables). They do not say much but they say enough for them to be used in different contexts without loosing the meaning they had when they were defined.

* A characteristic should be representative of a population of users.
* Developers are responsible of discovering characteristics but users should agree on the meaning they have to them in order for characteristics to be valid in Arcadia and used in services by companies.

Characteristics are composed of at least 4 parameters:

| Parameter | Role | Units of measure |
|:--|:--|:--|
| Data | Feed the characteristics that in turn feed the user's profile | `bytes` of data used for the characteristic |
| Algorithm | Show how data is used in order to get to the characteristic | `bytes` of data used for the  algorithm of the characteristic |
| Quality standard | Show that the algorithm used for the characteristic is genuine | `objective parameters` |
| Ground Truth | percentage that indicates the proportion of users satisfied with the degree of success of the characteristic with respect to their own personality | `percentage* of users` |

# The ground truth

How to be certain, at all times, that algorithms in Arcadia are getting better and generate results of the highest possible quality?

When a developer proposes a new algorithm for a characteristic of the digital profile, Arcadia runs an automated decentralised process that verifies that this algorithm performs better than the previous one. As there is no optimal *a priori* defined, we need to rely on dynamic `minimum performance` algorithm to establish the `ground truth`. This algorithm should specify the minimum performance any algorithm that comes after it should at least have.

How to build ground truths in a decentralised system?

* Use the scientific literature as the starting point.
* Engage with the users to get `feedback` on the performance of the algorithms.
* As more users upload more data and more developers extract knowledge from it, the `robustness` of each characteristic should increase.
