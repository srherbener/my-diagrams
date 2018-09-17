# simple make file to build diagrams

DIAGRAMS = \
  ioda_reader.png \
  ncdiag_flow.png \
  class_structure.png \
  obs_flow.png \
  multi_index_impl.png \
  db_api.png \
  big_picture_before.png \
  big_picture_now.png \
  big_picture_next.png \
  big_picture_final.png


all: $(DIAGRAMS)

# rule to build diagram
%.png: %.gv
	dot -T png -o $(@) $(<)
