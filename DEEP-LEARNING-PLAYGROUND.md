# Deep Learning Playground

Deep Learning Playground is an ongoing team project I’m working on through Data Science at Georgia Tech (DS@GT). It gives students a way to experiment with neural networks in a browser. A learner can choose or upload a dataset, assemble layers visually, and configure training options such as the optimizer, loss function, epochs, and batch size.

[DS@GT working repository](https://github.com/DataScience-GT/Deep-Learning-Playground) · [Project README on the nextjs branch](https://github.com/DataScience-GT/Deep-Learning-Playground/blob/nextjs/README.md)

## How the code is organized

| Component | Role |
| --- | --- |
| [Next.js frontend](https://github.com/DataScience-GT/Deep-Learning-Playground/tree/nextjs/frontend) | React interface for visual model building, training setup, learning modules, and a dashboard |
| [Django training service](https://github.com/DataScience-GT/Deep-Learning-Playground/tree/nextjs/training) | Training API with tabular, image, and audio routes. The local Docker Compose setup starts Django, a Celery worker, and Redis. |
| [Flask API](https://github.com/DataScience-GT/Deep-Learning-Playground/tree/nextjs/backend) | Additional backend routes for datasets, training, and experiment records |
| [Serverless services](https://github.com/DataScience-GT/Deep-Learning-Playground/tree/nextjs/serverless) and [Terraform](https://github.com/DataScience-GT/Deep-Learning-Playground/tree/nextjs/dlp-terraform) | SST/Lambda services and AWS infrastructure definitions |

## What’s verified

These notes describe the checked-in code on the club’s `nextjs` branch. The club README documents setup requirements, cloud dependencies, and gaps in the historical deployment. It also says the complete upload-to-training flow has yet to be reverified. This portfolio links to the team repository for source and development instructions.
