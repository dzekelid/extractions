---
name: ParallelDots
x-slug: paralleldots
description: ParallelDots is one of the best applied AI research groups in the world.
  We work with enterprises globally to tackle challenging business problems and create
  the winners of tomorrow. We also provide AI consulting services to explore the what,
  why, how and who about deploying AI in businesses. Try-out our cutting edge text
  analysis APIs and join the community of 1,000+ global users. Contact us at contact@paralleldots.com
  and tell us about the challenging business problems that you are facing.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/paralleldots-logo.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Extraction
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/extraction/master/_listings/paralleldots/apis.md
specificationVersion: "0.14"
apis:
- name: ParallelDots AI APIs Docs - Phrase Extractor
  x-api-slug: phrase-extractor-post
  description: |-
    # Introduction
    What does your API do?

    Get phrase keywords from the text in the input.

    # Overview
    Things that the developers should know about

    The API accepts the input parameters as form-data.

    Response will be in JSON as shown below:

    ```
    {
        "keywords": [
            {
                "relevance_score": 1,
                "keyword": "Ronaldo"
            },
            {
                "relevance_score": 2,
                "keyword": "Principality Stadium"
            },
            {
                "relevance_score": 1,
                "keyword": "Cardiff"
            },
            {
                "relevance_score": 1,
                "keyword": "last"
            },
            {
                "relevance_score": 1,
                "keyword": "June"
            },
            {
                "relevance_score": 2,
                "keyword": "Real Madrid"
            },
            {
                "relevance_score": 1,
                "keyword": "its"
            },
            {
                "relevance_score": 2,
                "keyword": "third champions"
            },
            {
                "relevance_score": 2,
                "keyword": "League trophy"
            }
        ],
        "usage": "By accessing ParallelDots API or using information generated by ParallelDots API, you are agreeing to be bound by the ParallelDots API Terms of Use: http://www.paralleldots.com/terms-and-conditions"
    }

    ```

    # Authentication
    What is the preferred way of using the API?

    An API key is required to be sent as a parameter to authenticate your requests.


    # Rate limit
    Is there a limit to the number of requests an user can send?

    There is no rate limit as such but too many concurrent requests will throw 504 time-out error from nginx.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/paralleldots-logo.png
  humanURL: https://www.paralleldots.com/
  baseURL: https://apis.paralleldots.com//v3
  tags: Machine Learning, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extraction/master/_listings/paralleldots/phrase-extractor-post-openapi.md
- name: ParallelDots AI APIs Docs - Phrase Extractor
  x-api-slug: phrase-extractor-post
  description: |-
    # Introduction
    What does your API do?

    Get phrase keywords from the text in the input.

    # Overview
    Things that the developers should know about

    The API accepts the input parameters as form-data.

    Response will be in JSON as shown below:

    ```
    {
        "keywords": [
            {
                "relevance_score": 1,
                "keyword": "Ronaldo"
            },
            {
                "relevance_score": 2,
                "keyword": "Principality Stadium"
            },
            {
                "relevance_score": 1,
                "keyword": "Cardiff"
            },
            {
                "relevance_score": 1,
                "keyword": "last"
            },
            {
                "relevance_score": 1,
                "keyword": "June"
            },
            {
                "relevance_score": 2,
                "keyword": "Real Madrid"
            },
            {
                "relevance_score": 1,
                "keyword": "its"
            },
            {
                "relevance_score": 2,
                "keyword": "third champions"
            },
            {
                "relevance_score": 2,
                "keyword": "League trophy"
            }
        ],
        "usage": "By accessing ParallelDots API or using information generated by ParallelDots API, you are agreeing to be bound by the ParallelDots API Terms of Use: http://www.paralleldots.com/terms-and-conditions"
    }

    ```

    # Authentication
    What is the preferred way of using the API?

    An API key is required to be sent as a parameter to authenticate your requests.


    # Rate limit
    Is there a limit to the number of requests an user can send?

    There is no rate limit as such but too many concurrent requests will throw 504 time-out error from nginx.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/paralleldots-logo.png
  humanURL: https://www.paralleldots.com/
  baseURL: https://apis.paralleldots.com//v3
  tags: Machine Learning, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/extraction/master/_listings/paralleldots/phrase-extractor-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://pagerduty.api.gallery.streamdata.io
- type: x-api-stack
  url: http://paralleldots.stack.network
- type: x-blog
  url: https://blog.paralleldots.com/
- type: x-developer
  url: https://www.paralleldots.com/ai-apis
- type: x-documentation
  url: https://docs.paralleldots.com/
- type: x-faq
  url: https://www.paralleldots.com/frequently-asked-questions
- type: x-github
  url: https://github.com/ParallelDots
- type: x-linkedin
  url: https://www.linkedin.com/company/3572541/
- type: x-openapi-gist
  url: https://gist.githubusercontent.com/kinlane/18095af6f37b04ffada94a3378ad9e8b/raw/8ce934fcf5ac1be679873ad12df8ed00b7c750e6/paralleldots-ai-api-openapi.json
- type: x-pricing
  url: https://www.paralleldots.com/pricing
- type: x-terms-of-service
  url: https://www.paralleldots.com/terms-and-conditions
- type: x-twitter
  url: https://twitter.com/ParallelDots
- type: x-website
  url: https://www.paralleldots.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---