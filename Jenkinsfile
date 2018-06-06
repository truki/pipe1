pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        echo 'Pipeline1 test'
      }
    }
    stage('Stage2') {
      agent any
      steps {
        sh '''#! /bin/bash

echo "Hello Pipeline!!"'''
      }
    }
  }
}