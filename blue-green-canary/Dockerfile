FROM quay.io/rhdevelopers/blue-green-canary
USER root
RUN chown -R 1001:0 /deployments && chgrp -R 0 /deployments && chmod -R g=u /deployments && chmod a+x /deployments/run-java.sh
USER 1001