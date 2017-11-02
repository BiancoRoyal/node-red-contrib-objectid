# node-red-contrib-objectid

This Node-Red node is to create an Object-Id for mongodb write operations from JSON inputs.

![flowshot](screenshots/screenshot2.png)

The selected property in `msg.payload` will be set to an Object-Id, 
you can also inject a 24 hex characters and the node creates 
a valid Object-Id property from it or raise an error if it is not valid.

For example: `msg.payload._id = "572dbc06f307c8682045c55c"`

If the target property is null/false/0, a random Object-Id is created.

## Config

![flowsprops](screenshots/property.png)

## License:
__MIT:__
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
