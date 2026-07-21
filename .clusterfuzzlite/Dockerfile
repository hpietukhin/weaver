FROM gcr.io/oss-fuzz-base/base-builder-rust@sha256:4541e7f7e3c8708c9fa55ec578eebbfd745987bef86bc06ed9a5ebfd8a6f42d3

COPY . $SRC/weaver
WORKDIR $SRC/weaver
COPY .clusterfuzzlite/build.sh $SRC/
