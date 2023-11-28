#FROM ghcr.io/ros-planning/moveit2_tutorials:rolling-tutorial
FROM rocm/tensorflow:latest

RUN python -m pip install -U pip &&\
    pip install -U pandas &&\
    pip install -U scikit-learn &&\
    python -m pip install -U matplotlib &&\
    sudo pip install openpyxl

ENTRYPOINT [ "bash" ]
#CMD ["bash"]
