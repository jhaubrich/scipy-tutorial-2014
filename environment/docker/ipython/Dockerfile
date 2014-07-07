# Runs the ipython notebook
FROM       reproducible/base
MAINTAINER Ana Nelson <ana@ananelson.com>

ADD notebooks /home/repro/

CMD ipython notebook --ip=* --pylab=inline --no-browser
EXPOSE 8888
