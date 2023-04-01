# VPC Lattice Demo

Demo stack for Amazon VPC Lattice.

## Installation

[![Launch Stack](https://cdn.rawgit.com/buildkite/cloudformation-launch-stack-button-svg/master/launch-stack.svg)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=vpclatticedemo&templateURL=https://s3.amazonaws.com/ianmckay-us-east-1/vpclatticedemo/template.yaml)

Click the above link to deploy the stack to your environment.

If you prefer, you can also manually upsert the [template.yaml](https://github.com/iann0036/vpc-lattice-demo/blob/main/template.yaml) stack from source.

Currently, the only tested region is `us-east-1`.

## Usage

The stack produces both an inbound and outbound Lambda function. To test, manually invoke the outbound function using any payload.
