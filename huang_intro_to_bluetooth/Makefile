all: simplescan rfcomm-client rfcomm-server l2cap-client l2cap-server

% : %.c
	gcc -g -o $@ $< -lbluetooth

clean:
	rm -f *~
	rm -f simplescan rfcomm-client rfcomm-server l2cap-client l2cap-server
