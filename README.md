# Helm Chart for GoCD Bulletin Board sample application

# Introduction

This chart installs the bulletin board sample application. It's intended use is as a demo application for GoCD build pipelines.

#Usage

helm install --set image.repository=<image name> --set image.tag=<image tag>  bulletin-board-helm-chart
