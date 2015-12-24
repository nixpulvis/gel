# Gel

This is an extremely simple interface to the OpenGL engine. It relies on little knowledge of OpenGL to use, and makes getting started faster by doing the proper setup and providing the proper hooks. This library is inspired by Racket's big bang family of functions from `htdp/universe`.

## The `Gel` Class

The main class `Gel` should be inherited in the class containing the top level logic for the program. This should be thought of as your main class, kind of like a main function.

```rb
class Example < Gel
    def setup
    end

    def draw
    end

    def loop
    end

    def keyboard
    end

    def special_keyboard
    end
end
```

## Objects

In addition to making setup of the basic OpenGL environment easier, Gel also provides a few objects that can be drawn. These make creating very simple animations easy.
