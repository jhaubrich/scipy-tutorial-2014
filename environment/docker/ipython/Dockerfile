# Runs the ipython notebook
FROM       reproducible/base
MAINTAINER Ana Nelson <ana@ananelson.com>

ADD notebooks /home/repro/
RUN chown -R root /home/repro
# RUN chmod -R 777 /home/repro

CMD ipython notebook --ip=* --pylab=inline --no-browser
EXPOSE 8888
