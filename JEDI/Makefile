# simple make file to build diagrams

DIAGRAMS = \
  nuopc.png


all: $(DIAGRAMS)

# rule to build diagram
%.png: %.gv
	dot -T png -o $(@) $(<)
