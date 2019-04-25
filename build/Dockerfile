FROM quay.io/operator-framework/helm-operator:v0.7.0
LABEL name="InsightEdge Operator" \
      vendor="Gigaspaces" \
      version="v14.0.1" \
      release="1" \
      summary="Real-Time Analytics Platform Operator" \
      description="InsightEdge is an in-memory real-time analytics platform for instant insights to action. It's an always-on platform for mission-critical applications across cloud, on-premise or hybrid. InsightEdge operationalizes machine learning and transactional processing, at scale; analyzing data as it's born, enriching it with historical context, for instant insights."

# Required Licenses
COPY licenses /licenses 

COPY helm-charts/ ${HOME}/helm-charts/
COPY watches.yaml ${HOME}/watches.yaml
