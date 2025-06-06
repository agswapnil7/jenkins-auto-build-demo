# Jenkins Auto Build Demo

This is a simple project to test automatic Jenkins builds triggered by GitHub push events.

## Files
- `Jenkinsfile`: Defines a simple CI pipeline.
- `app.sh`: Simulated build script that prints a message.

## Setup
1. Create a Jenkins Pipeline job.
2. Connect this GitHub repo in the SCM section.
3. Enable "GitHub hook trigger for GITScm polling".
4. Add a GitHub webhook pointing to: `http://<your-ip>:8080/github-webhook/` .
5. Push any change to trigger the pipeline!

