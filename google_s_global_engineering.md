# Google's global scale engineering

**Disclaimer #1, all content are from publicly available materials.**

**Disclaimer #2, all opinions are my own.**

This article is a high level description of how Google does global scale engineering, based on my 6 years of practice as a software engineer at Google, and observations on Google's broad engineering practices.

I have been fortunate to work at Google from 2013-08 to 2019-04, and recently joined a startup in SF as a founding engineer.

Among all of the things I learned during my Google tenure, I am particularly impressed and intrigued by Google's strength in building and operating global-scale software.

Despite being largely secretive about the details, this strength has been demonstrated in many of the most influential distributed system advancements of the past decade. To name just one prominent example, Hadoop has become a billion dollar industry sector, while in reality, similar systems inside Google not only has far better quality, and was actually only a few among close to hundred of such systems, which collectively supported Google's business.

Google treats global-scale engineering as one of its core business value, if not the single most critical one. Take for example the recently-announced Stadia gaming platform, similar products with much smaller scales are already available for quite a few years, but only Google has the capability to make it a truly global platform that are accessible to everyone around the globe.

Indeed, Google is almost only interested in global scale products [1]. Google has been willing to invest heavily on some of world’s most challenging technical problems. The best example probably be Waymo (now an independnet company under Alphebeta). It is clear that Google has committed to huge investment (judging from the 120 MM payout to Anthony Levandowski) when self-driving car was just about a research problem.Anything that could not reach global audience is promptly deprioritized or even shut down. Such examples are too much to count. For a prominent example, Google+, the social network services Google tried to push to customers, and have caused an global uproar from the customers, was recently shutdown (for nonbusiness customers).

Google's global scape engineering capacity is reflected in several key areas:

*   People management: global-scale engineering demands a global-scale engineering team. Google has more than 40k world-class software engineers, and an equal number of non-technical people, who also play indispensible roles in Google’s daily operation. They base in dozens of  offices across the globe. This global presence enables Google to attract the top-quality talents. These people possess vastly different personal and professional backgrounds; and are looking for different things when at Google. Companies with similar scale as Google, often have set up their remote offices to work things that are secondary to the company’s bottom and top lines. Not the case for Google. Use Google’s Borg team as an example, in addition to Google’s maib campus, Borg has critical parts being developed and maintained at Warsaw, and had SRE team at Zurich. And the collaboration has been since the inception of Borg in 2003.
*   Technology: Technology is the foundation, they provide tools for people to collaborate, optimize operations, create new business opportunities, and enable many other innovations. A global engineering organization cannot rely on third party providers. For these technologies are too challenging to build and too valuable to share. Google has built a complete suite of developer tools for engineers to do their best work. Google also pioneers numerous breakthrough in distributed systems, AI/ML, security, etc., which enables their software to remain performant, reliable, and secure.  Google own most of world’s planet-scale software products, and the scale and quality of these products are unmatched. There are simple numbers to show that Google’s presense in building and operating world’s large software systems are simply off-chart. Google has shown the ability to scale advanced technologies, which are nowhere to found elsewhere. Google not only built such systems, they also demand the planet-scale userbase to justify their investment. Google rep
*   Operations: How to make the technical infrastructure be utilized fully? How to correctly address short-term and long-term engineering goals and risks? Google pioneered SRE. Unlike the traditional operational personell, SRE is mandated to spend at least 50% of their time on writing software that automates the daily operations. This ensires the investment in operational excellence, which in turn guarantees the quality of the scalability and quality of the infrastructure and applications. Data driven decision making is embedded in everyone's daily work.
*   Business development: Combining these together, the capability needs to reflect in products that bring actual business value. We'll not go into details as the author is not familiar with this area.

Let's dive deep in the technical infrastructure. Google owns the full stack of their products. Data centers, cross-vontinent fiber links, custom servers, programming language and developer tools, multiple operating systems, foundational cluster services, middleware, application framework, big data, AI/ML framework and tools, consumer hardware, etc. In all these areas, Google is either the undisputed best, or one of the best which specialized in different aspects.

## Notes

1.  From the reverse perspective, Google appears inpropotionally incompetent in areas that do not benefit from a global scale engineering capacity. For example, Google has unable to become a real they to Amazon's retail and cloud businesses, which are 2 areas that requires strength in operational.
