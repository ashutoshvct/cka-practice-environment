
# Passing the exam with 100% score

https://awscloudengineer.com/clearing-cka-exam-with-100-result/

# cka-practice-environment

## Getting the environment up and ready

Make sure that you have docker-compose installed ([installation instructions](https://docs.docker.com/compose/install/)).

To start the lab environment you can do either of the following two:
* To use the prebuilt images run: `docker-compose up -d` and point your browser to `http://localhost` (preferred)
* To build the images yourself locally run: `docker-compose -f docker-compose-builder.yml up -d` and point your browser to `http://localhost`

Things to note:
* Use Ubuntu 16 machine.
* If your reload the `exam.html` it will reset the timer as the timer currently being used is jQuery based. - solution WIP
* Since we are using jQuery to initialize and connect to GateOne therefore the application needs to be reachable from your browser host on port 8080. - solution WIP

# More questions

https://github.com/ashutoshvct/k8s/tree/master/cka-exam



