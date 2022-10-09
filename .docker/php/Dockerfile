FROM php:8.1-fpm

RUN apt-get update

RUN echo "Installing PHP extensions...\n" \
    \
#    && docker-php-ext-install bcmath \
#    && docker-php-ext-install calendar \
#    && docker-php-ext-install dba \
#    && docker-php-ext-install exif \
#    && docker-php-ext-install pcntl \
#    && docker-php-ext-install sysvshm \
#    && docker-php-ext-install shmop \
#    && docker-php-ext-install sockets \
#    && docker-php-ext-install gettext \
#    && docker-php-ext-install mysqli \
    \
#    && apt-get install libffi-dev -y && docker-php-ext-install ffi \
#    && apt-get install libgd-dev -y && docker-php-ext-install gd \
#    && apt-get install libicu-dev -y && docker-php-ext-install intl \
#    && apt-get install libbz2-dev -y && docker-php-ext-install bz2 \
#    && apt-get install libenchant-2-dev -y && docker-php-ext-install enchant \
#    && apt-get install libgmp-dev -y && docker-php-ext-install gmp \
#    && apt-get install libc-client-dev libkrb5-dev -y && docker-php-ext-configure imap --with-kerberos --with-imap-ssl && docker-php-ext-install imap \
#    && apt-get install libldap2-dev -y && docker-php-ext-install ldap \
#    && apt-get install libpq-dev -y && docker-php-ext-install pgsql \
#    && apt-get install libpspell-dev -y && docker-php-ext-install pspell \
#    && apt-get install libsnmp-dev -y && docker-php-ext-install snmp \
#    && apt-get install libxml2-dev -y && docker-php-ext-install soap \
#    && apt-get install libtidy-dev -y && docker-php-ext-install tidy \
#    && apt-get install libxslt-dev -y && docker-php-ext-install xsl \
#    && apt-get install libzip-dev -y && docker-php-ext-install zip \
    \
#    && pecl install apcu-5.1.22 && docker-php-ext-enable apcu \
#    && apt-get install libcmark-dev -y && pecl install cmark-1.2.0 && docker-php-ext-enable cmark \
#    && pecl install dbase-7.1.1 && docker-php-ext-enable dbase \
#    && pecl install dio-0.2.1 && docker-php-ext-enable dio \
#    && pecl install ds-1.4.0 && docker-php-ext-enable ds \
#    && pecl install eio-3.0.0RC4 && docker-php-ext-enable eio \
#    && pecl install ev-1.1.5 && docker-php-ext-enable ev \
    # !Important! Event extension requires a Sockets extension.
#    && apt-get install libevent-dev libssl-dev -y && pecl install event-3.0.8 && docker-php-ext-enable event \
#    && apt-get install libfann-dev -y && pecl install fann-1.2.0RC2 && docker-php-ext-enable fann \
#    && apt-get install libgearman-dev libevent-dev uuid -y && pecl install gearman-2.1.0 && docker-php-ext-enable gearman \
#    && apt-get install libgraphicsmagick1-dev -y && pecl install gmagick-2.0.6RC1 && docker-php-ext-enable gmagick \
#    && apt-get install libgpgme-dev -y && pecl install gnupg-1.5.1 && docker-php-ext-enable gnupg \
#    && apt-get install libyaml-dev -y && pecl install yaml-2.2.2 && docker-php-ext-enable yaml \
#    && apt-get install libcurl4-openssl-dev -y && pecl install yar-2.3.2 && docker-php-ext-enable yar \
#    && apt-get install libyaz-dev -y && pecl install yaz-1.2.4 && docker-php-ext-enable yaz \
#    && pecl install sync-1.1.2 && docker-php-ext-enable sync \
#    && pecl install swoole-4.8.12 && docker-php-ext-enable swoole \
#    && pecl install svm-0.2.3 && docker-php-ext-enable svm \
#    && apt-get install libssl-dev -y && pecl install stomp-2.0.3 && docker-php-ext-enable stomp \
#    && pecl install yac-2.3.1 && docker-php-ext-enable yac \
#    && pecl install yaconf-1.1.2 && docker-php-ext-enable yaconf \
#    && pecl install yaf-3.3.5 && docker-php-ext-enable yaf \
#    && apt-get install libxml2-dev -y && pecl install xmlrpc-1.0.0RC3 && docker-php-ext-enable xmlrpc \
#    && apt-get install libxml2-dev -y && pecl install xmldiff-1.1.3 && docker-php-ext-enable xmldiff \
#    && apt-get install zlib1g-dev -y && pecl install xlswriter-1.5.2 && docker-php-ext-enable xlswriter \
#    && pecl install inotify-3.0.0 && docker-php-ext-enable inotify \
#    && pecl install igbinary-3.2.7 && docker-php-ext-enable igbinary \
#    && pecl install parle-0.8.3 && docker-php-ext-enable parle \
    \
    && echo "\nThe extensions are successfully installed."

# Set working directory
WORKDIR /var/www
