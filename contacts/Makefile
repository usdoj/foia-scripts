all: contacts

contacts:
	python processing_time_scraper.py
	python convert_to_json.py

test:
	nosetests

setup:
	pip install -r requirements.txt

.PHONY: all contacts setup test
