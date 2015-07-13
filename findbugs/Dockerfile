FROM java
RUN curl -L http://downloads.sourceforge.net/project/findbugs/findbugs/3.0.1/findbugs-3.0.1.tar.gz | tar xz
COPY exclude.xml .
CMD ["findbugs-3.0.1/bin/findbugs", "-xml", "-quiet", "-exclude", "exclude.xml"]
