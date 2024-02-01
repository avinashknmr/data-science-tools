OWNER?=avinashknmr
version := python-3.9
build:
	docker build -t $(OWNER)/app/data-science/jupyterhub/base-notebook:$(version) ./base-notebook
	docker build -t $(OWNER)/app/data-science/jupyterhub/spark-notebook:$(version) ./spark-notebook --build-arg OWNER=$(OWNER)