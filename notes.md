-- Fetch package issue: full url to path wasn't provided.
-- Extact package path : 'remote_src: true' added to point to remote servers.
-- Disabled an optional task. 'copy_binaries.yml' since we are using url for data fetch.
-- Generate JKS cert. Java installation needs to be available on the control node and also a .bin folder needs to be in the root directory of execution.
-- mariadb [a:b] instances need to run for rhsso config to run without error.