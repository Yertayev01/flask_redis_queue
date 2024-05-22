FROM python:3.10-alpine

RUN pip install rq-dashboard

# https://github.com/rq/rq/issues/1469
RUN pip uninstall -y click
RUN pip install click==7.1.2

EXPOSE 9181

<<<<<<< HEAD
CMD ["rq-dashboard"]
=======
CMD ["rq-dashboard"]
>>>>>>> f66a52617985123e168983bc2b2168846dd154f3
