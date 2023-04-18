build:
	pip3 install -r requirements.txt

.PHONY: clean

clean:
	rm -f *.pyc

clean_output_files:
	rm -f output-*.txt
run:
	# python3 assignment.py $(ARGS)
	# source .venv/bin/activate
	# ../.venv/bin/python start_new_thread_example.py -n 3
	# ../.venv/bin/python threading_lock_acquire_release_example.py -n 3
	../.venv/bin/python threading_semaphore_example.py -n 5 -s 3