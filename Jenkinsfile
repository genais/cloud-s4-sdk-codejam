#!/usr/bin/env groovy 

String pipelineVersion = "v17"

node {
    deleteDir()
    sh "git clone --depth 1 https://github.com/SAP/cloud-s4-sdk-pipeline.git -b ${pipelineVersion} pipelines"
    load './pipelines/s4sdk-pipeline.groovy'
}
