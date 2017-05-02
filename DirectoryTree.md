```
middleware-experiment/
├── .editorconfig
├── .gitignore
├─┬ .vscode
│ └── launch.json
├── LICENSE
├── README.md
├─┬ node-webui
│ ├── .eslintrc.json
│ ├── .gitignore
│ ├── app.js
│ ├─┬ bin
│ │ └── www
│ ├── package.json
│ ├─┬ public
│ │ ├── favicon.ico
│ │ ├─┬ javascripts
│ │ │ ├── .eslintrc.json
│ │ │ ├── script-history.js
│ │ │ └── script-index.js
│ │ └─┬ stylesheets
│ │   ├── style.css
│ │   └── style.styl
│ ├─┬ routes
│ │ └── index.js
│ └─┬ views
│   ├── error.pug
│   ├── history.pug
│   ├── index.pug
│   └── layout.pug
├─┬ node
│ ├── .eslintrc.json
│ ├── README.md
│ ├── index.js
│ └── package.json
├─┬ ruby
│ ├── .rubocop.yml
│ ├── Gemfile
│ ├── Gemfile.lock
│ ├── doc
│ └── index.rb
└── shot.png

15 directories, 81 files

node-api-gate/
├── .codeclimate.yml
├── .dockerignore
├── .editorconfig
├── .eslintignore
├── .eslintrc
├── .gitignore
├── .tern-project
├── Dockerfile
├── LICENSE.md
├── README.md
├── app.js
├─┬ bin
│ ├── block-for-mysql.js
│ └── www.js
├─┬ config
│ └── config.js
├─┬ controller
│ ├── dns-create.js
│ ├── dns-main.js
│ ├── dns-search.js
│ ├── hypervisor-block-main.js
│ ├── hypervisor-block-vbd.js
│ ├── hypervisor-block-vdi.js
│ ├── hypervisor-health.js
│ ├── hypervisor-main.js
│ ├── hypervisor-net.js
│ ├── hypervisor-vif.js
│ ├── hypervisor-vm.js
│ ├── index.js
│ ├── syslog.js
│ └── task.js
├─┬ helper
│ ├── amqp-sender.js
│ ├── dns-check.js
│ ├── healthcheck.js
│ ├── strig-sanitize.js
│ ├── syslog-normalize.js
│ └── xen-check.js
├─┬ migrations
│ ├── 0000-create-user.js
│ ├── 0001-create-vm-user.js
│ ├── 0002-create-dns-record.js
│ ├── 0003-create-task.js
│ ├── 0004-VMDistros-migration.js
│ ├── 0005-VMTemplates-migration.js
│ ├── 0006-populate-distro.js
│ └── 0007-populate-dummy-admin.js
├─┬ models-mongo
│ ├── index.js
│ ├── syslog.js
│ └── task.js
├─┬ models
│ ├── dns_record.js
│ ├── index.js
│ ├── task.js
│ ├── user.js
│ ├── vm-distro.js
│ ├── vm-template.js
│ └── vm-user.js
└── package.json

7 directories, 53 files

node-frontend/
├── .codeclimate.yml
├── .dockerignore
├── .editorconfig
├── .eslintignore
├── .eslintrc
├── .gitignore
├── .pug-lintrc
├── .tern-project
├── Dockerfile
├── LICENSE
├── README.md
├── app.js
├─┬ assets
│ ├─┬ _javascripts
│ │ ├── 000_For_Protected_Scripts_Only
│ │ ├── alpine.js
│ │ ├── fhana.js
│ │ ├── kalafina.js
│ │ ├── report.js
│ │ ├── status.js
│ │ └── tooru.js
│ ├─┬ _stylesheets
│ │ └── report.scss
│ ├─┬ javascripts
│ │ ├── 000_For_Public_Facing_Or_Library
│ │ ├── Date.js
│ │ ├── MobileCheck.js
│ │ ├── confirm.js
│ │ ├── ie10-quickfix.js
│ │ ├── lightybox.js
│ │ └── status.js
│ └─┬ stylesheets
│   └── style.scss
├─┬ bin
│ ├── block-for-mysql.js
│ └── www.js
├─┬ config
│ └── config.js
├─┬ controllers
│ ├─┬ admin
│ │ ├── assets.js
│ │ ├── auth.js
│ │ ├── dns.js
│ │ ├── index.js
│ │ ├── instances-api.js
│ │ ├── instances.js
│ │ ├── profile.js
│ │ ├── status.js
│ │ └── user.js
│ ├── api.js
│ ├── help.js
│ ├── index.js
│ ├── status.js
│ └─┬ users
│   ├── assets.js
│   ├── auth.js
│   ├── dns.js
│   ├── index.js
│   ├── instances-api.js
│   ├── instances.js
│   └── profile.js
├── gulpfile.js
├─┬ helpers
│ ├── authenticator.js
│ └── promise-http.js
├─┬ models
│ ├── index.js
│ └── user.js
├── nodemon.json
├── package.json
├─┬ private
│ └─┬ assets
│   ├── alpine.js
│   ├── fhana.js
│   ├── kalafina.js
│   ├── report.css
│   ├── report.js
│   ├── status.js
│   └── tooru.js
├─┬ public
│ └─┬ assets
│   ├─┬ images
│   │ ├── chrome-s03.png
│   │ ├── chrome-s04.png
│   │ ├── chrome-s05.png
│   │ ├── chrome-s06.png
│   │ └── chrome-s07.png
│   ├─┬ javascripts
│   │ ├── Date.js
│   │ ├── MobileCheck.js
│   │ ├── confirm.js
│   │ ├── ie10-quickfix.js
│   │ ├── lightybox.js
│   │ └── status.js
│   └─┬ stylesheets
│     └── style.css
└─┬ views
  ├─┬ _partials
  │ ├── ssh-chrome.pug
  │ ├─┬ vm-partials
  │ │ ├── net-list.pug
  │ │ ├── tpl-list.pug
  │ │ ├── vif-list.pug
  │ │ └── vm-list.pug
  │ └─┬ vm-tabs
  │   ├── vm-all.pug
  │   ├── vm-net.pug
  │   ├── vm-rcrd.pug
  │   ├── vm-tpl-all.pug
  │   ├── vm-tpl-rcrd.pug
  │   └── vm-vif.pug
  ├─┬ admin
  │ ├─┬ _partials
  │ │ ├── dns-edit-form.pug
  │ │ ├── dns-table.pug
  │ │ ├── user-edit-form.pug
  │ │ ├── user-edit.pug
  │ │ ├── user-list.pug
  │ │ ├── user-new.pug
  │ │ └── vm-navbar.pug
  │ ├── dns.pug
  │ ├── index.pug
  │ ├── instances.pug
  │ ├── login.pug
  │ ├── profile.pug
  │ ├── report-dns.pug
  │ ├── report-syslog.pug
  │ ├── report-user.pug
  │ ├── status.pug
  │ └── user.pug
  ├── error.pug
  ├── help.pug
  ├─┬ includes
  │ ├── breadcrumb-f.pug
  │ ├── breadcrumb.pug
  │ ├── common-topbar-user.pug
  │ ├── footer-f.pug
  │ ├── footer-js.pug
  │ ├── footer.pug
  │ ├── lightbox.pug
  │ ├── loading-bar.pug
  │ ├── mobile_not_supported-f.pug
  │ ├── mobile_not_supported.pug
  │ ├── old-browser-warning.pug
  │ ├── status-list-group.pug
  │ ├── status-syslog-ovv.pug
  │ └── topmenu.pug
  ├── index.pug
  ├─┬ layouts
  │ ├── fluid.pug
  │ ├── normal.pug
  │ └── report.pug
  ├── status.pug
  └─┬ user
    ├─┬ _partials
    │ ├── dns-edit-form.pug
    │ ├── dns-edit.pug
    │ ├── dns-form.pug
    │ ├── dns-table.pug
    │ ├── password-generate.pug
    │ └── vm-navbar.pug
    ├── dns.pug
    ├── index.pug
    ├── instances.pug
    ├── login.pug
    └── profile.pug

29 directories, 137 files

node-keepalive/
├── Dockerfile
├── LICENSE
├── README.md
├── index.js
└── package.json

0 directories, 5 files

ruby-dns/
├── .codeclimate.yml
├── .docker-repository.yml
├── .env.example
├── .gitignore
├── .rubocop.yml
├── Dockerfile
├── Gemfile
├── Gemfile.lock
├── LICENSE
├── README.md
├── Rakefile
├── amqpd.rb
├── apid.rb
├── bootstrapper-amqpd.sh
├── bootstrapper-dnsd.sh
├── config.ru
├── dnsd.rb
├─┬ migrations
│ └── 0001_bootstrap.rb
├── screenshot.png
└── supervisord.conf

1 directories, 20 files

xen-api/
├── .codeclimate.yml
├── .dockerignore
├── .rubocop.yml
├── Dockerfile
├── Gemfile
├── Gemfile.lock
├── LICENSE
├── README.md
├── docker // Docker-Specifc Codes
├── docs
├── messages.rb
├── screenshot.png
├── supervisord.conf
└── xenapi.rb

11 directories, 83 files
```
