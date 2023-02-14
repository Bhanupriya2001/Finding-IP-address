import java.net.*;
import java.io.*;

public class LocalHost {
  public static void main(String[] args) {
    try {
      InetAddress address = InetAddress.getByName("localhost");
      Socket socket = new Socket(address, 8080);

      // Send and receive data from the socket
      // ...

      socket.close();
    } catch (UnknownHostException e) {
      System.err.println("Host not found");
    } catch (IOException e) {
      System.err.println("I/O error");
    }
  }
}
