# simple make file to build diagrams

DIAGRAMS = \
  big_picture_before.png \
  big_picture_now.png \
  big_picture_next.png \
  big_picture_final.png


all: $(DIAGRAMS)

# rule to build diagram
%.png: %.gv
	dot -T png -o $(@) $(<)
