# PreFormatted coding
## Indent
Indents as you think proper.

* Indent length is 2 and space-only. Because dislike dependent tab length.

good coding:

    if x > 0
      if y > 0
        puts “x > 0 && y > 0”
      end
    end

# display digit
* characters per line is 80.
 * (rubric) maybe normal-width 
 * (rubric) no-reason

# blank-line
* separate some classes.
* separate methods, attributes, inner class; but ignore first/last line

good coding:

    class Foo
      …
    end
     
    class Bar
      …
    end

bad coding:

    class Foo
      …
    end
    class Bar
      …
    end

good coding:
    
    class Foo
      attr :bar
       
      def baz
        …
      end
      
      def quux
        …
      end
    end

bad coding:

    class Foo
    
      attr :bar
       
      def baz
        …
      end
      
      def quux
        …
      end
    
    end
