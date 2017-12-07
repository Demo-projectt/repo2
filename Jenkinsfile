#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/Demo-projectt/repo2.git'],
    pipelineTriggers([githubPush()])])

node {
   stage 'build'
   echo 'hello boy'
   stage 'test'
   echo 'bomb'
}
