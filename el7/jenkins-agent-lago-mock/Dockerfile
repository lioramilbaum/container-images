FROM local/jenkins-virtualization-jnlp-agent

RUN yum install -y mock
COPY systemd/* /etc/systemd/system/
RUN systemctl enable var-cache-mock.mount var-lib-mock.mount var-lib-lago.mount