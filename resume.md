# Chris Koskey

**Staff Software Engineer · Platform & DevOps**

[koskey@gmail.com](mailto:koskey@gmail.com) · Portland, OR (open to remote) · [linkedin](https://linkedin.com/in/koskey) · [github](https://github.com/pausebreak) · [more about me](https://github.com/pausebreak/me)

## Summary

Staff engineer focused on the platform and the tooling other engineers use every day: AWS and Terraform, CI/CD, access, and developer experience. Has been building build systems for new products since 2008, and brings 20+ years of full stack work to knowing what the platform has to serve. Aims for systems that are easy to use and understand, however complex they are underneath.

## Skills

- **Cloud and infrastructure:** AWS, Terraform, Docker, Kubernetes, Tailscale, nginx, Linux
- **CI/CD and tooling:** GitHub Actions, shell scripting, LaunchDarkly, aws-vault, build and test automation
- **Access and security:** Google Workspace SSO, AWS IAM, account on/offboarding, threat assessment, audits and patching, dependency review
- **Data:** PostgreSQL (schema design, migrations, query optimization, read replicas), data warehousing and ETLs, S3
- **AI:** AWS Bedrock
- **Languages:** TypeScript, JavaScript, Node.js, SQL; React and D3 on the frontend

## Experience

### Staff Software Engineer

**Ghosts Inc., 2022-2026**\
_B2B marketplace for bulk excess goods (product: Ghost)._

- Joined as the second engineer, and the first at Staff level, when the company was 35 people. It has grown to 200, with 16 engineers.
- Took over a contractor-built codebase and CI and reshaped it into a secure, low-friction setup.
- Built the CI/CD pipelines in GitHub Actions from the ground up.
- Run the AWS platform in Terraform, along with Docker, Tailscale, LaunchDarkly, and message-based services.
- Own the Postgres database: schema design, migrations, query optimization, and the ETLs into the data warehouse. Adopted postgres.js, whose parameterized queries rule out SQL injection.
- Moved AWS IAM access to Google Workspace SSO and required aws-vault for credentials, which closed the path a previous drive-by supply-chain attack had used.
- Manage account onboarding and offboarding across the platform and all third-party services.
- Built the infrastructure for an internal AI chat assistant: AWS Bedrock so data never goes to frontier model providers, and a read-only Postgres replica so the model's queries never touch production.
- Introduced RFCs for technical decisions; the team's engineering standards are written down there.
- Lenders reviewing the company during funding said they had never seen an early-stage company with security and engineering this strong.

### Staff Software Engineer

**OpenGov, 2019-2022**\
_Government software used by thousands of US public agencies, from states to small towns, with heavy load at fiscal year end._

- With two Portland colleagues, changed how engineering worked across the company, making developer experience a goal alongside standards and testing.
- Helped an acquired Boston team go from no tests to a suite that let them make large changes with confidence.
- Started a monthly Dependabot review so dependencies stopped going stale; confirmed issues went into the next sprint.
- Maintained Postgres schemas and migrations, optimized queries, and taught teams how to avoid SQL injection.
- Delivered nearly every project on schedule by trading scope for time and breaking work into smaller pieces.
- Tech lead on products across functions, and mentor to a dozen engineers in Portland, California, and Boston.
- Worked with GitHub Actions and brought story mapping into planning.

### Senior Software Engineer

**OpenGov, 2016-2019**

- Led products as the company grew from startup to mid-size.
- Bootstrapped Node.js projects and shared frameworks.
- Worked with microservices on Kubernetes and Docker, Jenkins, Webpack, Yarn, nginx, Keycloak, LaunchDarkly, Postgres, Rails, Redshift, and S3.
- Wrote an interactive React SVG charting library on D3's core structures.

## Earlier Experience

**Senior Software Developer, Tripwire, 2008-2016.** Built new build systems for new products, along with their project layout, test frameworks, and automation. Full stack development in JavaScript, D3, Java, and Clojure.

**Owner, Relative Path, 2007-2012.** Ruby consultancy run alongside Tripwire; REST services in Rack, Sinatra, and DataMapper.

**Senior Developer, ANZUS Technology / S&K Technologies, 2003-2008.** US Forest Service environmental cleanup tracking site. Set up AIX and Linux servers, handled release management, and packaged an Apache/PHP/Oracle installer deployed nationwide.

**Developer / System Administrator, BigBlueBang.com, 2002-2003.** Web hosting startup: ran DNS, web, database, FTP, and mail as FreeBSD jailed services.

## Projects

**darts** - [github.com/pausebreak/darts](https://github.com/pausebreak/darts)\
Free web app for scoring a darts game in real time. React with Zustand and Immer, time-travel (undo/redo) state, sound, and text-to-speech.

## Outside Work

Lifelong musician; writes, produces, and self-releases music as Closure Club.
