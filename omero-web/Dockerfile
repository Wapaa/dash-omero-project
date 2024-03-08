FROM gitlab-registry.in2p3.fr/fbi-data/dockers-projects/omero-web/omero-web:latest
USER root
COPY omero-dash-webapp/omerodash /opt/omero/web/venv3/lib/python3.8/site-packages/omerodash
COPY omero-dash-webapp/omero_dash_webapp.egg-info /opt/omero/web/venv3/lib/python3.8/site-packages/omerodash-0.1.0-py3.8.egg-info

COPY omero-dash-webapp/config.omero  /opt/omero/web/config/config.omero
RUN /opt/omero/web/venv3/bin/pip install bootstrap4
RUN /opt/omero/web/venv3/bin/pip install bootstrap4
RUN /opt/omero/web/venv3/bin/pip install bootstrap4
RUN /opt/omero/web/venv3/bin/pip install bootstrap4
USER omero-web
#RUN pip install bootstrap4 -target /opt/omero/web/venv3/lib/python3.8/site-packages