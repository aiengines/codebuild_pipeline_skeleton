# codebuild_pipeline_skeleton
An example of using a Codebuild pipeline with troposphere for CI/CD


## Get started

Fork the repository.

Create a gh token by going to 'https://github.com/settings/tokens' and generate a new Personal
access token which has permissions over your repository (it needs to create hooks to trigger
codebuild).


```
virtualenv -p(which python3) py3
source py3/bin/activate
pip install -r requirements.txt
```

Then just re-create the pipeline using CF
```
./CodePipeline.py
```

This create a pipeline that is triggered on commits on the given repository.
