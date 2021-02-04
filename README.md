# nnels-local-d7-lando
Lando configuration for a local development NNELS app

## Setup ##

Pre-requisite: [Install Lando](https://docs.lando.dev/basics/installation.html)

`git clone https://github.com/BCLibCoop/nnels-local-d7-lando.git nnels-local-d7 && cd nnels-local-d7`

#### Extract web root ####
`tar xzvf nnels-local-d7-web.tar.gz`

#### Build Lando app ####
`lando start`

`lando db-import nnels_drupal7_local_SCRUBBED+TRIMMED.sql.gz`
