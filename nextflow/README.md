# Nextflow for rMATS

* [rmatsTurbo.nf](rmatsTurbo.nf) is a Nextflow ([https://www.nextflow.io](https://www.nextflow.io)) implementation of the rMATS workflow with BAM files as input

## Run

### Locally

* Install: [https://www.nextflow.io/docs/latest/install.html](https://www.nextflow.io/docs/latest/install.html)
* Edit [nextflow.config](nextflow.config)
* Run:
```bash
nextflow run rmatsTurbo.nf --config nextflow.config -resume
```

### On the cloud

Nextflow can be configured to run on the cloud. More details can be found in the Nextflow [documentation](https://www.nextflow.io/docs/latest/aws.html). Another option is to use [https://seqera.io/platform/](https://seqera.io/platform/). With a compute environment set up in Seqera rMATS can be launched by specifying the pipeline (https://github.com/Xinglab/rmats-turbo) and filling in the parameters
