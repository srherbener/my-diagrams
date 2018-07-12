# simple make file to build diagrams

DIAGRAMS = \
  odb_ioda.png \
  odb1_table_org.png


all: $(DIAGRAMS)

# rule to build diagram
%.png: %.gv
	dot -T png -o $(@) $(<)
