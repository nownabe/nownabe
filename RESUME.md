# Shogo Watanabe ([@nownabe](https://github.com/nownabe))

[Twitter](https://twitter.com/nownabe) / [Email](mailto:nownabe+resume@gmail.com)

Software engineering with 6+ years of experience in developing applications and architecting systems, and Pre-sales engineering with 2+ years of experience.

## Skills

* Go, Ruby, Python, TypeScript, JavaScript
* MySQL, Spanner, Firestore, BigQuery
* Google Cloud, Amazon Web Services
* Terraform, Kubernetes, Docker, Linux
* RESTful, gRPC, Git, SQL, HTML/CSS
* Customer-facing, technical consulting

## Work Experience
### Customer Engineer // [Google Cloud Japan G.K.](https://cloud.google.com)

**January 2020 to present**

* Led [Tech Acceleration Program](https://cloud.google.com/solutions/in-house-development-support)
  (TAP) in the manufacturing industry. TAP is an architecting and prototyping 3-day workshop where we dive
  into clients' businesses, conduct domain modeling, design ideal architecture, and build prototypes
  through mob programming.
* Designed and created demos and hands-on workshops. [Cloud Demo Portal](https://github.com/GoogleCloudPlatform/appengine-cloud-demo-portal) is a web application demonstrating some Google Cloud products on browsers, written in Go, TypeScript (Next.js), and Terraform. Other small demos and hands-on materials are on [GitHub](https://github.com/orgs/ShawnLabo/repositories).
* Provided best practices on Google Cloud, architecture review sessions, and engineering enablement
  sessions regarding Google Cloud and cloud-native skills.
* Closed several deals successfully with large Japanese enterprises, having discussions 
  with stakeholders, discovering their objectives and concerns, digging into their potential problems,
  proposing appropriate solutions, making architecture designs, delivering product hands-on
  sessions, driving their PoCs, and troubleshooting their applications.
* Organized team logistics: 1) team dashboards for operational excellence, which allows team members to collect accurate information. 2) automated several routine works with chatbots.

<details>
<summary>Public references I was involved in:</summary>

* [富士通：Google Cloud の活用で IT 企業から DX 企業への "変革" を後押し | Google Cloud 公式ブログ](https://cloud.google.com/blog/ja/topics/customers/fujitsu-transforming-to-dx-company-by-leveraging-google-cloud)
* [京セラドキュメントソリューションズ: リフトからシフトへ！ サーバーレス環境構築の内製化への取り組み](https://cloudonair.withgoogle.com/events/naiseika-day?talk=session1-2)
* [パナソニックインフォメーションシステムズ: Smart Factory (IIoT Platform)　誕生秘話と今後の展望](https://cloudonair.withgoogle.com/events/naiseika-day?talk=session2-1)
* [東急: DX 推進における内製化の 3 つのポイント](https://cloudonair.withgoogle.com/events/naiseika-day?talk=session2-3)
* [ジェイアール東海情報システム株式会社: 設備異常通知システムの短期開発に、Tech Acceleration Program を利用 | Google Cloud 公式ブログ](https://cloud.google.com/blog/ja/products/application-development/jtis-tech-acceleration-program)
* [東芝テック株式会社: クラウド版 POS システムのアーキテクチャ刷新に向けて、Tech Acceleration Program を利用 | Google Cloud 公式ブログ](https://cloud.google.com/blog/ja/products/application-development/toshibatec-tech-acceleration-program)
* [ヤマハ発動機: アプリからのデータ活用に挑戦 Tech Acceleration Program を活用 | Google Cloud 公式ブログ](https://cloud.google.com/blog/ja/products/application-development/yamaha-motor-tech-acceleration-program)
</details>

### Software Engineer // [Wondershake Ltd.](https://wondershake.com/)

**August 2017 to December 2019**

* Migrated the infrastructure of applications from VM-based architecture on AWS to containerized architecture on Google Kubernetes Engine, restructuring applications to optimize them into containerized architecture.
* Built a simple recommendation engine for pictures based on the cosine similarity of recognized objects in pictures in order to replace unlicensed pictures in articles with similar licensed pictures. The engine was written in Go, and the UI was written with React.
* Developed a machine learning model to classify articles with scikit-learn, Python. Built and provided the prediction API on the model as a gRPC API.
* Launched multi-cloud data processing platform: transfer access logs and application logs from AWS to Google Cloud, transform raw data into well-formatted data on Cloud Dataflow, and load data into BigQuery.
* Tuned backend API performance to render rapidly on mobile and to reduce backend load.

### Backend Tech Lead // [Goodpatch Inc.](https://global.goodpatch.com/)

**May 2016 to July 2017**

* Launched a new product as a tech lead of backend apps, designing the architecture and implementing backend applications with Go and Kubernetes to provide a RESTful API for a single page application. Worked closely with the frontend engineers, designers, and the product team.
* Architected applications, directed the tech team, improved EngProd, and educated junior developers as a tech lead.
* Optimized backend applications written with Ruby on Rails and MongoDB; for example, I made copying projects of a product twice faster by avoiding a lot of N+1 queries.

### Software Engineer // [IDC Frontier Inc.](https://www.idcf.jp/en/company/)

**April 2013 to April 2016**

* Launched '[load balancer as a service](https://www.idcf.jp/cloud/ilb/)' in [IDCF Cloud](https://www.idcf.jp/en/cloud/) (Japanese domestic public cloud). Designed the whole architecture that scaled based on each component and implemented them with Ruby, RabbitMQ, Percona XtraDB Cluster, Influx DB, and HA proxy. 
  * Developed an asynchronous, idempotent job worker framework, and built two applications with it. The provisioning worker configured and operated LB instances, networks, and other infrastructure in idempotent ways. Another application tested the capabilities of self-healing by injecting failures into infrastructure components.
  * Built other components too; Agents were embedded in LB instances to operate and configure them, subscribing to command queues. Metrics Collectors embedded in LB instances collected metrics like traffic and CPU usage. Aggregator aggregates metrics to trigger automatic operations such as recovering from failure and charging users for traffic.
* Published API clients for cloud services as open-source software on GitHub.
* Collaborated with international teams in the US and India.
* Communicated with internal teams and stakeholders to integrate applications, infrastructure, security, network, and operations and to get agreements on business requirements.

## Education

* [Master of Computer Science, University of Tsukuba](https://www.cs.tsukuba.ac.jp/english/), Japan (2013)
* [Bachelor of Informatics, University of Tsukuba](https://inf.tsukuba.ac.jp/en/), Japan (2011)
* [Associate degree in Electrical and Computer Engineering, National Institute of Technology, Akashi College](https://www.akashi.ac.jp/english/dept/el.html), Japan (2009)

## Supplemental Information

### Certifications

* [Fundamental Information Technology Engineer Examination (基本情報技術者試験)](https://www.jitec.ipa.go.jp/1_11seido/fe.html)
* [Google Cloud Certified Professional Cloud Architect](https://www.credential.net/dc0918cf-765a-4327-9742-848076422e14)
* [Google Cloud Certified Professional Cloud Developer](https://www.credential.net/76739be8-3318-419f-a4d4-954143f806e7)
* [Google Cloud Certified Professional Cloud Database Engineer](https://www.credential.net/93139e70-f906-41ab-b21c-4fc474363907)

### Languages

* Japanese (Native)
* English (Business Intermediate)

### Personality

* I love dogs and live with my adorable [Shiba dog](https://www.instagram.com/shibadogruby/).
* I like playing online video games, reading comics, walking my dog, traveling, and doing snow sports.
* I like coding; solving everyday problems by creating software, it has been my life work since I was a kid.

### Public Links

* [GitHub](https://github.com/nownabe)
  * [Overview about me](https://github.com/nownabe/nownabe/blob/main/README.md)
  * [Work history in detail (WIP)](https://github.com/nownabe/nownabe/blob/main/WORK_HISTORY.md)
* [DEV.to](https://dev.to/nownabe) - Tech articles
* [Zenn](https://zenn.dev/nownabe) - Tech articles (ja)
* [Qiita](https://qiita.com/nownabe) - Tech articles (ja)
* [nownab.log](https://blog.nownabe.com/) - Personal blog (ja)
* [LinkedIn](https://www.linkedin.com/in/nownabe/)
* [AtCoder](https://atcoder.jp/users/nownabe) - Competitive programming service

