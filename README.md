# SportVU
#Day 1 02/01
import xml.etree.ElementTree as ET

tree = ET.parse("ALL DATA H1.XML")
root = tree.getroot()
print (root)
