# c0-pipelines
This pipeline is designed to create other pipelines. To use:
1. fly the ci/concourse-pipelines.yml pipeline into your concourse. Set the parameters as necessary.
1. Add a new directory with a pipeline and params file. Use hello-world as an example
2. Add that pipeline to the pipelines.yml file [could be automated]
3. See new pipeline is detected and created in concourse

