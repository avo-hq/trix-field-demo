# README

This is a minimal reproduction to show thow Avo works with Action Text and Trix

## Installation

```bash
git clone https://github.com/avo-hq/trix-field-demo
cd trix-field-demo
bundle install
bin/rails server
```

### Commands we ran to set up this repo.

```bash
rails new trix-field-demo
cd trix-field-demo
bin/rails action_text:install
bin/rails app:template LOCATION='https://avohq.io/app-template'
```