# ClusterFuzzLite build image for DelegationBench fuzz targets.
# Base image digest pinned for reproducible builds; Dependabot tracks it.
FROM gcr.io/oss-fuzz-base/base-builder-python@sha256:58f80c90a90944b68b8e70b98e38997ee9396225311cfb0f3aea78671446ab4e

COPY . $SRC/delegationbench
WORKDIR $SRC/delegationbench
COPY .clusterfuzzlite/build.sh $SRC/build.sh
