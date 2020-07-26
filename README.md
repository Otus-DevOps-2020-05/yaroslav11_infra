# yaroslav11_infra
yaroslav11 Infra repository

# Homework 5
Open ssh connection to SomeInternalHost(with internal ip: 10.130.0.34) via BastionHost(with global ip: 130.193.48.244):
ssh -i ~/.ssh/appuser -A -J appuser@130.193.48.244 appuser@10.130.0.34

bastion_IP = 130.193.48.244
someinternalhost_IP = 10.130.0.34
