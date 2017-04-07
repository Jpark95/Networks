The server returns N copies of the string that the client
sends it, intead of just one copy.  N is passed into the server as a
command-line argument

The client prints out the value of N, learned by analyzing
the length of the string that the server returns. The client
learns N only by analyzing the server's reply.
