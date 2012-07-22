graphviz_network_vyatta
=======================

Working Sample Network

# graphviz install for debian
$ sudo apt-get install -y graphviz

# graphviz install for redhat
$ sudo yum install -y graphviz

# txt to pdf
$ dot -T pdf simple.txt > simple.pdf
$ dot -T pdf vyatta.txt > vyatta.pdf
$ dot -T pdf vmvyatta.txt > vmvyatta.pdf

# PDF Application
# Edit LibreOffice3.5
# Read Only AdobeReader

# txt to png
$ dot -T png simple.txt -o simple.png
$ dot -T png vyatta.txt -o vyatta.png
$ dot -T png vmvyatta.txt -o vmvyatta.png

