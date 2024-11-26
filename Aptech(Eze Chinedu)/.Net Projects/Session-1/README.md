# Indomie Noodles Cooking Guide

## Table of Contents
1. [Ingredients](#ingredients)
2. [Equipment Needed](#equipment-needed)
3. [Instructions](#instructions)
4. [Tips and Variations](#tips-and-variations)


## Ingredients
- 4 pack of Indomie noodles (any flavor)
- 2 cups of water
- Optional add-ins:
  - Egg
  - Protein (e.g., crayfish)
  - Seasoning (e.g., pepper, salt)

## Equipment Needed
- Pot
- Gas Cooker
- Spoon or fork
- Bowl for serving(not really important since you can just eat from the pot, less stress)

## Instructions
1. **Boil Water**  
   - Pour 2 cups of water into a pot and place it on the stove over medium heat. Allow the water to come to a boil.

2. **Add Noodles**  
   - Once the water is boiling, carefully add the Indomie noodles. Let them cook for about 2–3 minutes.

3. **Add Seasoning**  
   - Open the seasoning packet that comes with the noodles and add it to the pot. Stir well to combine.

4. **Add Optional Ingredients**  
   - now is the time to throw in your extras! You can add them directly to the pot and cook for an additional 1–2 minutes, or until everything is heated through. If you want to add an egg, crack it into the pot and stir quickly to scramble it. but thats just one of the many ways you can use eggs with your noodles, you could also boil seperately or try frying it, your pot your choice.

5. **Serve**  
   - Once the noodles and any add-ins are cooked to your liking, turn off the heat. Carefully pour the noodles into a bowl or leave it in the pot.

6. **Enjoy**  
   - Your Indomie noodles are ready! Enjoy them while they're hot.

## Tips and Variations
- **Spice it Up**: If you like spicy food, consider adding chili pepper or hot sauce.
- **Make It Healthier**: Incorporate a variety of vegetables to boost the nutritional content. A bit stressful though if you're considering a fast meal.
- **Experiment with Flavors**: Try different flavors of Indomie noodles or mix and match seasoning packets like the (Adomine product) for a unique taste.













using System;

namespace ExampleApp
{
    // Define a class named 'Person'
    class Person
    {
        // Define properties (variables) with different data types
        public string Name { get; set; }
        public int Age { get; set; }
        public double Height { get; set; }
        public bool IsStudent { get; set; }

        // Define a method to display the person's details
        public void DisplayDetails()
        {
            Console.WriteLine($"Name: {Name}");
            Console.WriteLine($"Age: {Age}");
            Console.WriteLine($"Height: {Height} meters");
            Console.WriteLine($"Is Student: {IsStudent}");
        }

        // Define a method to calculate the year of birth
        public int CalculateYearOfBirth()
        {
            int currentYear = DateTime.Now.Year;
            return currentYear - Age;
        }
    }

    class Program
    {
        static void Main(string[] args)
        {
            // Create an instance of the 'Person' class
            Person person = new Person();

            // Assign values to the properties
            person.Name = "John Doe";
            person.Age = 25;
            person.Height = 1.75;
            person.IsStudent = true;

            // Call the method to display the person's details
            person.DisplayDetails();

            // Call the method to calculate the year of birth and display it
            int yearOfBirth = person.CalculateYearOfBirth();
            Console.WriteLine($"Year of Birth: {yearOfBirth}");
        }
    }
}
