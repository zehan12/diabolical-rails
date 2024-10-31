The boring generator introduces following generators:

-  Install Tailwind CSS: rails generate boring:tailwind:install
- Install Bootstrap: rails generate boring:bootstrap:install
- Install JQuery: rails generate boring:jquery:install
- Install FontAwesome via Yarn: rails generate boring:font_awesome:yarn:install
- Install FontAwesome via RubyGems: rails generate boring:font_awesome:ruby_gem:install
- Install Bullet: rails generate boring:bullet:install
- Install Audit gems(bundler-audit, ruby_audit): rails generate boring:audit:install
- Install Pry gems for easy debugging: rails generate boring:pry:install
- Install Active Storage for Google Cloud Service: rails generate boring:active_storage:google:install
- Install Active Storage for AWS: rails generate boring:active_storage:aws:install
- Install Active Storage for Azure: rails generate boring:active_storage:azure:install
- Install CircleCI: rails generate boring:ci:circleci:install --repository_name=<name> --ruby_version=<version>
- Install GitHub Actions: rails generate boring:ci:github_action:install --repository_name=<name> --ruby_version=<version>
- Install Travis CI: rails generate boring:ci:travisci:install --ruby_version=<version>
- Install Rubocop: rails generate boring:rubocop:install --ruby_version=<version> --test_gem=<test_framework_name>
Build Favicon: rails generate boring:favicon:build --application_name=<application_name> --favico_letter=<favico_letter> --primary_color=<color>
- Install Pundit: rails generate boring:pundit:install
- Install GraphQL: rails generate boring:graphql:install
- Install SimpleForm: rails generate boring:simple_form:install --css_framework=<css_framework>
- Install Devise: rails generate boring:devise:install
- Install Devise Facebook Omniauth: rails generate boring:oauth:facebook:install
- Install Devise GitHub Omniauth: rails generate boring:oauth:github:install
- Install Devise Google Omniauth: rails generate boring:oauth:google:install
- Install Devise Twitter Omniauth: rails generate boring:oauth:twitter:install
- Install Twilio: rails generate boring:twilio:install
- Install Ahoy: rails generate boring:ahoy:install
- Install Stripe: rails generate boring:payments:stripe:install
- Install Stimulus: rails generate boring:stimulus:install
- Install Rails Admin: rails generate boring:rails_admin:install
- Install Paper Trail: rails generate boring:paper_trail:install
- Install Flipper: rails generate boring:flipper:install
- Install RSpec: rails generate boring:rspec:install
- Install FactoryBot: rails generate boring:factory_bot:install
- Install Faker: rails generate boring:faker:install
- Install Overcommit with RuboCop: rails generate boring:overcommit:pre_commit:rubocop:install
- Install Letter Opener: rails generate boring:letter_opener:install
- Install Whenever: rails generate boring:whenever:install
- Install Rswag: rails generate boring:rswag:install --rails_port=<rails_app_port> --authentication_type=<api_authentication_type> --skip_api_authentication=<skip_api_authentication> --api_authentication_options=<api_authentication_options> --enable_swagger_ui_authentication=<enable_swagger_ui_authentication>
- Install Webmock: rails generate boring:webmock:install --app_test_framework=<test_framework>
- Install Figjam: rails generate boring:figjam:install
- Install Pronto with Gitlab CI: rails generate boring:pronto:gitlab_ci:install
- Install Pronto with Github Action: rails generate boring:pronto:github_action:install
- Install Rack Mini Profiler: rails generate boring:rack_mini_profiler:install
- Install VCR: rails generate boring:vcr:install --testing_framework=<testing_framework> --stubbing_libraries=<stubbing_libraries>
- Install Avo: rails generate boring:avo:install
- Install Doorkeeper with devise: rails generate boring:devise:doorkeeper:install
- Install Sentry: rails generate boring:sentry:install --use_env_variable --breadcrumbs_logger=<breadcrumbs_logger_options>
- Install Dotenv: rails generate boring:dotenv:install
- Install Honeybadger: rails generate boring:honeybadger:install
- Install Rails ERD: rails generate boring:rails_erd:install
- Install Annotate: rails generate boring:annotate:install
- Install CanCanCan: rails generate boring:cancancan:install
- Install Gitlab CI: rails generate boring:ci:gitlab_ci:install