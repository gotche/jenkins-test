
node ('small') {

  stage "Requirements Installation"

  checkout scm

  sh '''#!/bin/bash
    set -x
    git clean -x -f -d
    echo Hello
    echo $? > .status_requirements
  '''

  stage "DB Setup"

  sh '''#!/bin/bash
        echo DB setup
        echo $? > .status_db
  '''
}
