72.1.1

package q11391;
import java.util.*;

public class SimpleArrayListDemo {
    public static void main(String[] args) {
        List<String> namesList = new ArrayList<String>();
        namesList.add("Hyderabad");
        namesList.add("Bangalore"); // Corrected spelling
        namesList.add("Chennai");
        
        for (String name : namesList) { // Corrected the syntax for iterating over the list
            System.out.println(name.substring(0, 3));
            // Print the String up to 3 characters using substring method
        }
    }
}

72.1.2

In a code for India 
CA is code for Canada

73.1.1. 

package q35981;

import java.util.*;

public class GenericListDemo {

    public static void main(String[] args) {

        List<Integer> numbersList = new ArrayList<>();

        numbersList.add(72);
        numbersList.add(78);
        numbersList.add(81);

        int total = 0;

        for (int number : numbersList) {
            total += number;
        }

        System.out.println("total = " + total);
    }
}


73.1.2.

In statement 1, class A is called a non-generic class.


In statement 2, class B is called a generic class.



73.1.3.

Statement 6 will not result in compilation errors.



74.1.1

Statement 1 is an example of raw type.

Statement 2 and Statement 3 mean the same.

Compiler will produce a type conversion warning for Statement 5.

Compiler will not produce a type conversion warning for Statement 6.





75.1.1

package q11394;

public class CustomGenericClassExample {

    public static void main(String[] args) {

        A<String> al = new A<>("Ganga");
        System.out.println("al.getValue(): " + al.getValue());

        A<Boolean> a2 = new A<>(true);
        System.out.println("a2.getValue(): " + a2.getValue());
    }
}

class A<T> {
    private T value;

    public A(T value) {
        this.value = value;
    }

    public T getValue() {
        return value;
    }
}

76.1.1

package q11395;

import java.util.*;

public class BoundedTypeExample {

    public static void main(String[] args) {
        List<String> namesList = new ArrayList<>();
        namesList.add("Ganga");
        namesList.add("Krishna");

        Set<String> namesSet = new LinkedHashSet<>();
        namesSet.add("Ganga");
        namesSet.add("Narmada");

        System.out.println("largerCollection : " + largerCollection(namesList, namesSet));
    }

    // Define a generic method that takes two collections using the generic type parameter <T extends Collection>
    public static <T extends Collection<?>> T largerCollection(T collection1, T collection2) {
        return (collection1.size() > collection2.size()) ? collection1 : collection2;
    }
}

77.1.1

package q11396;

import java.util.*;

public class WildCardTypesDemo {

    public static void main(String[] args) {

        List<? extends Number> upperList = Arrays.asList(2, -3, 4);
        List<? super Number> lowerList = new ArrayList<>();
        List<Integer> noBoundsList = new ArrayList<>();

        upperBoundedMethod(upperList);
        lowerBoundedMethod(lowerList);
        noBoundedMethod(noBoundsList);
    }

    public static void upperBoundedMethod(List<? extends Number> list) {
        System.out.println("In upperBoundedMethod");
        for (Number number : list) {
            System.out.println(number);
        }
    }

    public static void lowerBoundedMethod(List<? super Integer> list) {
        System.out.println("In lowerBoundedMethod");
        list.add(2);
        list.add(3);
        list.add(4);
        System.out.println("list: " + list);
    }

    public static void noBoundedMethod(List<Integer> list) {
        System.out.println("In noBoundedMethod");
        list.add(8);
        list.add(7);
        System.out.println("list: " + list);
    }
}

78.1.1

package q11367;

import java.util.*;

public class ArrayListDemo {

    public static void main(String[] args) {
        List alist = new ArrayList();

        System.out.println("aList.size() = " + alist.size());
        System.out.println("aList = " + alist);

        alist.add("First Entry");
        alist.add("Second Entry");

        System.out.println("aList.size() = " + alist.size());
        System.out.println("aList = " + alist);

        List blist = new ArrayList(alist);

        System.out.println("bList.size() = " + blist.size());
        System.out.println("bList = " + blist);

        List clist = new ArrayList(20);

        System.out.println("cList.size() = " + clist.size());
        System.out.println("cList = " + clist);
    }
}

78.1.2

package q35988;

import java.util.*;

public class ArrayListIterationDemo {

    public static void main(String[] args) {

        List<String> namesList = new ArrayList<>();

        for (String argument : args) {
            if (Character.isUpperCase(argument.charAt(0))) {
                namesList.add(argument);
            }
        }

        for (String name : namesList) {
            System.out.println(name);
        }

        for (int i = 0; i < namesList.size(); i++) {
            System.out.println("Name at index " + i + " is : " + namesList.get(i));
        }
    }
}

78.1.3

package q11955;

import java.util.*;

public class ArrayListIterationDemo {

    public static void main(String[] args) {

        List<String> namesList = new ArrayList<>();

        for (String arg : args) {
            if (Character.isUpperCase(arg.charAt(0))) {
                namesList.add(arg);
            }
        }

        for (String name : namesList) {
            System.out.println(name);
        }
    }
}

78.1.4

package q23673;

import java.util.*;

public class ArrayListIterationDemo {

    public static void main(String[] args) {

        List<String> namesList = new ArrayList<>();

        for (String arg : args) {
            namesList.add(arg);
        }

        for (int i = 0; i < namesList.size(); i++) {
            System.out.println("Name at index " + i + " is : " + namesList.get(i));
        }
    }
}

78.1.5

package q23676;

import java.util.*;

public class ArrayListIterationDemo {

    public static void main(String[] args) {

        List<String> namesList = new ArrayList<>();

        for (String arg : args) {
            namesList.add(arg);
        }

        if (namesList.size() > 2) {
            System.out.println("Name at index 2 is : " + namesList.get(2));
        } else {
            System.out.println("There is no element at index 2.");
        }
    }
}

78.1.6

package q24085;

import java.util.*;

public class ArrayListDemo {

    public static void main(String[] args) {

        List<String> namesList = new ArrayList<>();

        for (String arg : args) {
            namesList.add(arg);
        }

        System.out.println(namesList);
        System.out.println("Size of the list is : " + namesList.size());
    }
}

78.1.7

package q35985;

import java.util.*;

public class ArrayListMethodsDemo {

    public static void main(String[] args) {

        List<String> alist = new ArrayList<>(args.length);

        for (String argument : args) {
            alist.add(argument);
        }

        System.out.println("aList = " + alist);
        System.out.println("aList.size() = " + alist.size());

        Object removedElement = alist.remove(3);
        System.out.println("removedElement = " + removedElement);
        System.out.println("aList = " + alist);

        alist.set(0, "Steve Jobs");
        System.out.println("aList = " + alist);

        alist.add(0, "Bill Gates");
        System.out.println("aList = " + alist);
    }
}

79.1.1

package q36170;

import java.util.*;

public class TreeSetDemo {

    public static void main(String[] args) {

        Set<String> namesSet = new TreeSet<>();

        Scanner scanner = new Scanner(System.in);

        String str1 = scanner.nextLine();
        namesSet.add(str1);

        String str2 = scanner.nextLine();
        namesSet.add(str2);

        namesSet.add("Budha");

        System.out.println("namesSet = " + namesSet);

        namesSet.add("Budha");

        System.out.println("namesSet = " + namesSet);

        namesSet.remove(str2);

        System.out.println("namesSet = " + namesSet);

        scanner.close();
    }
}

79.1.2

package q37263;

import java.util.*;

public class TreeSetDemo {

    public static void main(String[] args) {

        Set<String> namesSet = new TreeSet<>();

        Scanner scanner = new Scanner(System.in);

        String str;

        for (int i = 0; i < 3; i++) {
            str = scanner.nextLine();
            namesSet.add(str);
        }

        System.out.println("namesSet = " + namesSet);

        str = scanner.nextLine();
        namesSet.add(str);

        System.out.println("namesSet = " + namesSet);

        for (int i = 0; i < 2; i++) {
            str = scanner.nextLine();
            namesSet.remove(str);
        }

        System.out.println("namesSet = " + namesSet);

        scanner.close();
    }
}


80.1.1

package q37264;

import java.util.*;

public class HashMapDemo {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        HashMap<String, String> aMap = new HashMap<>();

        System.out.println("aMap.size() = " + aMap.size());
        System.out.println("aMap = " + aMap);

        String key1, value1;
        key1 = scanner.nextLine();
        value1 = scanner.nextLine();

        String key2, value2;
        key2 = scanner.nextLine();
        value2 = scanner.nextLine();

        String key3, value3;
        key3 = scanner.nextLine();
        value3 = scanner.nextLine();

        String key4, value4;
        key4 = scanner.nextLine();
        value4 = scanner.nextLine();

        aMap.put(key1, value1);
        aMap.put(key2, value2);
        aMap.put(key3, value3);
        aMap.put(key4, value4);

        System.out.println("aMap.size() = " + aMap.size());
        System.out.println("aMap = " + aMap);

        HashMap<String, String> bMap = new HashMap<>(aMap);

        System.out.println("bMap.size() = " + bMap.size());
        System.out.println("bMap = " + bMap);

        HashMap<String, String> cMap = new HashMap<>(20);

        System.out.println("cMap.size() = " + cMap.size());
        System.out.println("cMap = " + cMap);

        scanner.close();
    }
}

80.1.2

package q37267;

import java.util.*;

public class HashMapPutMethodDemo {

    public static void main(String[] args) {

        Map<String, String> namesMap = new HashMap<>();

        Scanner input = new Scanner(System.in);

        // read two strings representing key1 and value1
        String key1, value1;
        key1 = input.nextLine();
        value1 = input.nextLine();
        namesMap.put(key1, value1);

        // read two strings representing key2 and value2
        String key2, value2;
        key2 = input.nextLine();
        value2 = input.nextLine();
        namesMap.put(key2, value2);

        // read two strings representing key3 and value3
        String key3, value3;
        key3 = input.nextLine();
        value3 = input.nextLine();
        namesMap.put(key3, value3);

        // print namesMap
        System.out.println("namesMap = " + namesMap);

        input.close(); // Closing the Scanner object to prevent resource leak
    }
}

80.1.3

package q37268;

import java.util.*;

public class HashMapGetMethodDemo {

    public static void main(String[] args) {

        Map<String, String> namesMap = new HashMap<>();

        Scanner input = new Scanner(System.in);

        namesMap.put("Sun", "Sunday");
        namesMap.put("Mon", "Monday");
        namesMap.put("Tue", "Tuesday");
        namesMap.put("Thu", "Thursday");

        System.out.println("namesMap = " + namesMap);

        System.out.println("Enter key to get value: ");
        String key = input.nextLine();

        String result = namesMap.get(key);

        System.out.println("value mapped to Tue is : " + result);

        input.close();
    }
}

80.1.4

package q37266;

import java.util.*;

public class HashMapMethodsDemo {

    public static void main(String[] args) {

        Map<String, String> namesMap = new HashMap<>();

        Scanner input = new Scanner(System.in);

        String key1, value1;
        key1 = input.nextLine();
        value1 = input.nextLine();
        namesMap.put(key1, value1);

        String key2, value2;
        key2 = input.nextLine();
        value2 = input.nextLine();
        namesMap.put(key2, value2);

        String key3, value3;
        key3 = input.nextLine();
        value3 = input.nextLine();
        namesMap.put(key3, value3);

        System.out.println("namesMap = " + namesMap);

        System.out.println("value mapped to " + key2 + " is : " + namesMap.get(key2));

        System.out.println("Enter value to change for " + key2 + " : ");
        String x = input.nextLine();
        namesMap.put(key2, x);

        System.out.println("namesMap = " + namesMap);

        System.out.println("new value mapped to " + key2 + " is : " + namesMap.get(key2));

        System.out.println("namesMap.size() = " + namesMap.size());

        input.close(); 
    }
}

80.1.5

package q37269;

import java.util.*;

public class CharcountDemo {

    public static void main(String[] args) {

        HashMap<Character, Integer> namesMap = new HashMap<>();

        Scanner scanner = new Scanner(System.in);

        String str = scanner.nextLine();

        for (int i = 0; i < str.length(); i++) {
            char c = str.charAt(i);
            if (namesMap.containsKey(c)) {
                namesMap.put(c, namesMap.get(c) + 1);
            } else {
                namesMap.put(c, 1);
            }
        }

        System.out.println(namesMap);

        scanner.close();
    }
}

80.1.6

package q36018;

import java.util.*;

public class HashMapIterationDemo {

    public static void main(String[] args) {

        Map<String, String> namesMap = new HashMap<>();

        for (String argument : args) {
            String shortName = argument.substring(0, 3);
            namesMap.put(shortName, argument);
        }

        Set<String> shortNameset = new HashSet<>(namesMap.keySet());

        for (String key : shortNameset) {
            System.out.println(key + " : " + namesMap.get(key));
        }
    }
}

80.1.7

import java.util.*;

public class HashMapIterationDemo {

    public static void main(String[] args) {

        Map<String, String> namesMap = new HashMap<>();

        for (String str : args) {
            String key = str.substring(0, 2);
            namesMap.put(key, str);
        }

        Set<String> shortNamesSet = new HashSet<>(namesMap.keySet());

        for (String key : shortNamesSet) {
            System.out.println(key + " : " + namesMap.get(key));
        }
    }
}

80.1.8

package q36021;

import java.util.*;

public class HashMapIterationDemo {

    public static void main(String[] args) {

        HashMap<String, String> namesMap = new HashMap<>();

        for (String str : args) {
            String key = str.substring(0, 3);
            namesMap.put(key, str);
        }

        Set<Map.Entry<String, String>> entrySet = namesMap.entrySet();

        for (Map.Entry<String, String> entry : entrySet) {
            String key = entry.getKey();
            String value = entry.getValue();
            System.out.println(key + " : " + value);
        }
    }
}

80.1.9

package q24086;

import java.util.*;

public class HashMapIterationDemo {

    public static void main(String[] args) {

        Map<String, String> namesMap = new HashMap<>();

        Set<String> shortNamesSet = namesMap.keySet();

        for (String str : args) {
            String key = str.substring(0, 2);
            namesMap.put(key, str);
        }

        System.out.println(namesMap);
    }
}


81.1.1

package q37270;

import java.util.*;

public class ArrayDequeDemo {

    public static void main(String[] args) {

        ArrayDeque<String> arrayDeque = new ArrayDeque<>();

        Scanner input = new Scanner(System.in);

        String str1 = input.nextLine();
        String str2 = input.nextLine();
        String str3 = input.nextLine();

        arrayDeque.offer(str1);
        arrayDeque.offer(str2);
        arrayDeque.offer(str3);

        System.out.println("after all offers calls : " + arrayDeque);

        System.out.println("poll returns : " + arrayDeque.poll());

        System.out.println("after calling poll : " + arrayDeque);

        String str4 = input.nextLine();
        String str5 = input.nextLine();

        arrayDeque.push(str4);
        arrayDeque.push(str5);

        System.out.println("after all push calls : " + arrayDeque);

        System.out.println("pop returns : " + arrayDeque.pop());

        System.out.println("after calling pop : " + arrayDeque);

        String str6 = input.nextLine();
        String str7 = input.nextLine();

        arrayDeque.offerFirst(str6);
        arrayDeque.offerLast(str7);

        System.out.println("arrayDeque after offerFirst and offerLast calls : " + arrayDeque);

        input.close();
    }
}

81.1.2

package q37271;

import java.util.*;

public class ArrayDequeDemo {

    public static void main(String[] args) {

        ArrayDeque<String> arrayDeque = new ArrayDeque<>();

        Scanner scanner = new Scanner(System.in);

        String str1 = scanner.nextLine();
        String str2 = scanner.nextLine();
        String str3 = scanner.nextLine();

        arrayDeque.offer(str1);
        arrayDeque.offer(str3);
        arrayDeque.offer(str2);

        System.out.println("after all offers calls : " + arrayDeque);

        scanner.close();
}
}

81.1.3

package q37272;

import java.util.*;

public class ArrayDequeDemo {

    public static void main(String[] args) {

        ArrayDeque<String> arrayDeque = new ArrayDeque<>();

        Scanner scanner = new Scanner(System.in);

        String str1 = scanner.nextLine();
        String str2 = scanner.nextLine();
        String str3 = scanner.nextLine();

        arrayDeque.offer(str1);
        arrayDeque.offer(str3);
        arrayDeque.offer(str2);

        System.out.println("after all offers calls : " + arrayDeque);

        System.out.println("poll returns : " + arrayDeque.poll());

        System.out.println("after calling poll : " + arrayDeque);

        System.out.println("peek returns : " + arrayDeque.peek());

        System.out.println("after calling peek : " + arrayDeque);

        scanner.close();
    }
}

82.1.1

Package q29348;
import java.util.Scanner;
import java.util.TreeSet;

public class LongestWordFinder {

    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter a sentence:");
        String sentence = scanner.nextLine();

        String[] words = sentence.split("\\s+");

        TreeSet<String> wordSet = new TreeSet<>(String.CASE_INSENSITIVE_ORDER);

        for (String word : words) {
            wordSet.add(word);
        }

        int maxLength = 0;
        for (String word : wordSet) {
            maxLength = Math.max(maxLength, word.length());
        }

        for (String word : wordSet) {
            if (word.length() == maxLength) {
                System.out.println(word);
            }
        }
    }
}

82.1.2

package q30035;
import java.util.ArrayList;
import java.util.Collections;
import java.util.Scanner;

public class SecondLargestElement {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        ArrayList<Integer> list = new ArrayList<>();

        while (scanner.hasNextInt()) {
            list.add(scanner.nextInt());
        }

        if (list.size() < 2) {
            System.out.println("Insufficient elements");
        } else {
            Collections.sort(list);
            int secondLargest = list.get(list.size() - 2);
            System.out.println(secondLargest);
        }
    }
}

82.1.3

package q30034;
import java.util.ArrayDeque;
import java.util.Deque;
import java.util.Scanner;

public class SlidingWindowProduct {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter the elements of the 
        String[] inputArray = scanner.nextLine().split(" ");
        int[] array = new int[inputArray.length];
        for (int i = 0; i < inputArray.length; i++) {
            array[i] = Integer.parseInt(inputArray[i]);
        }

        // Prompt the user to enter the window size 
        int windowSize = scanner.nextInt();

        printSlidingWindowProducts(array, windowSize);
    }

    public static void printSlidingWindowProducts(int[] array, int windowSize) {
        Deque<Integer> deque = new ArrayDeque<>();

        // Calculate product of first window
        int product = 1;
        for (int i = 0; i < windowSize; i++) {
            deque.offerLast(array[i]);
            product *= array[i];
        }
        System.out.println(product);

        // Calculate product of remaining windows
        for (int i = windowSize; i < array.length; i++) {
            int removedElement = deque.pollFirst();
            deque.offerLast(array[i]);
            product = (product / removedElement) * array[i];
            System.out.println(product);
        }
    }
}

82.1.4

import java.util.HashMap;
import java.util.Map;
import java.util.Scanner;

public class EmployeeDatabase {
    private static final Map<String, String> employeeMap = new HashMap<>();

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        boolean running = true;

        while (running) {
            System.out.println("1. Add Employee");
            System.out.println("2. Delete Employee");
            System.out.println("3. Search Employee by Name");
            System.out.println("4. Exit");
            int choice = scanner.nextInt();
            scanner.nextLine(); // Consume newline

            switch (choice) {
                case 1:
                    addEmployee(scanner);
                    break;
                case 2:
                    deleteEmployee(scanner);
                    break;
                case 3:
                    searchEmployee(scanner);
                    break;
                case 4:
                    running = false;
                    break;
                default:
                    System.out.println("Invalid choice");
            }
        }
    }

    private static void addEmployee(Scanner scanner) {
        System.out.print("Employee name: ");
        String name = scanner.nextLine();
        System.out.print("Department: ");
        String department = scanner.nextLine();
        employeeMap.put(name, department);
        System.out.println("Employee added");
    }

    private static void deleteEmployee(Scanner scanner) {
        System.out.print("Enter employee name to delete: ");
        String name = scanner.nextLine();
        if (employeeMap.containsKey(name)) {
            employeeMap.remove(name);
            System.out.println("Employee deleted");
        } else {
            System.out.println("Employee not found");
        }
    }

    private static void searchEmployee(Scanner scanner) {
        System.out.print("Enter employee name to search: ");
        String name = scanner.nextLine();
        if (employeeMap.containsKey(name)) {
            
            System.out.println("Department: " + employeeMap.get(name));
        } else {
            System.out.println("Employee not found");
        }
    }
}

