#!/bin/bash

# Update and upgrade packages
pkg update && pkg upgrade -y

# Install essential packages
pkg install -y wget curl git

# Install Python
pkg install -y python

# Install Node.js
pkg install -y nodejs

# Install OpenSSH
pkg install -y openssh

# Install Vim (text editor)
pkg install -y vim

# Set up storage access
termux-setup-storage

# Upgrade pip
pip install --upgrade pip

# Install Metasploit Framework
pkg install -y unstable-repo
pkg install -y metasploit

# Create symbolic links for msfvenom and other Metasploit binaries
ln -s $PREFIX/opt/metasploit-framework/msfvenom /data/data/com.termux/files/usr/bin/msfvenom
ln -s $PREFIX/opt/metasploit-framework/msfconsole /data/data/com.termux/files/usr/bin/msfconsole
ln -s $PREFIX/opt/metasploit-framework/msfdb /data/data/com.termux/files/usr/bin/msfdb

# Install compiling environment (gcc)
pkg install -y clang

# Install Netcat (network utility)
pkg install -y netcat

# Install Nmap (network scanner)
pkg install -y nmap

# Install the Android SDK tools
pkg install -y android-tools

# Install Ruby
pkg install -y ruby

# Install Java
pkg install -y openjdk-17

# Install a network monitoring tool (iftop)
pkg install -y iftop

# Install Htop (interactive process viewer)
pkg install -y htop

# Install Termux API (access Android features)
pkg install -y termux-api

# Install Tsudo (root privileges)
pkg install -y tsu

# Install Wireshark (network protocol analyzer)
pkg install -y wireshark

# Install Hydra (brute force attack tool)
pkg install -y hydra

# Install SQLMap (SQL injection tool)
pkg install -y sqlmap

# Install John the Ripper (password cracker)
pkg install -y john

# Install the Aircrack-ng suite (WiFi security testing tools)
pkg install -y aircrack-ng

# Install Nikto (web server scanner)
pkg install -y nikto

echo "Setup complete! Your Termux environment is now professionally configured."
