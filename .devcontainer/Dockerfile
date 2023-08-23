FROM npslearninglab/watery_robots:vrx_current

COPY setup_env.sh /tmp/

RUN mkdir -p ~/vrx_ws/src
RUN cd ~/vrx_ws/src
RUN git clone https://github.com/osrf/vrx.git

RUN sudo chmod +x /tmp/setup_env.sh
RUN /tmp/setup_env.sh