# Installation guide

## Essential Libraries

``` bash
sudo apt-get install build-essential git debhelper autotools-dev dh-autoreconf iptables protobuf-compiler libprotobuf-dev pkg-config libssl-dev dnsmasq-base ssl-cert libxcb-present-dev libcairo2-dev libpango1.0-dev iproute2 apache2-dev apache2-bin iptables dnsmasq-base gnuplot iproute2 apache2-api-20120211 libwww-perl
```

## Mahimahi Setup

``` bash
git clone https://github.com/ravinet/mahimahi
```

``` bash
cd mahimahi
```

``` bash
./autogen.sh && ./configure && make
```

``` bash
sudo make install
```

``` bash
cd ..
```

## Sourdough

``` bash
git clone https://github.com/keithw/sourdough
```

``` bash
cd sourdough
```

``` bash
./autogen.sh && ./configure && make
```

``` bash
sudo sysctl -w net.ipv4.ip_forward = 1
```
