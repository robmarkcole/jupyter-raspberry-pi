# jupyter-raspberry-pi
Using Jupyter notebooks on a raspberry pi 3. Installed Rasbian stretch `2018-06-27-raspbian-stretch`

Following https://www.hackster.io/mjrobot/rpi-physical-computing-using-jupyter-notebook-056fa8 we simply:
```
$ sudo pip3 install jupyter
$ sudo ipython3 kernelspec install-self
$ jupyter notebook
```
Then head to `http:localhost:8888`. I'm not sure how to expose port 8888 so I can access the server from my Macbook. Also system python is 3.5.3 so will need to update.
