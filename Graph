graph={
'A':['B','C','D'],
'B':['E','F'],
'C':['G','H'],
'D':['I'],
'E':['J'],
'F':['K','L'],
'G':['M'],
'H':[],
'I':['N','O'],
'J':[],
'K':[],
'L':[],
'M':[],
'N':[],
'O':[]
}
def bfs(visit,graph,current_node):
	visit.append(current_node)
	queue=[ ]
	queue.append(current_node)
	while queue:
		s=queue.pop(0)
		print(s)
		for neighbour in graph[s]:
			if neighbour not in visit:
				visit.append(neighbour)
				queue.append(neighbour)
bfs([ ],graph,'A')
