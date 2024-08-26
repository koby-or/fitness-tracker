// מודל נתונים
const exerciseCategories = ['כוח עליון', 'כוח תחתון', 'ליבה', 'אירובי'];

class Exercise {
  constructor(name, category) {
    this.name = name;
    this.category = category;
    this.personalBest = 0;
    this.history = [];
  }

  addWorkout(weight, reps) {
    const date = new Date().toISOString().split('T')[0];
    this.history.push({ date, weight, reps });
    if (weight > this.personalBest) {
      this.personalBest = weight;
    }
  }
}

class User {
  constructor(name, age, weight, targetWeight) {
    this.name = name;
    this.age = age;
    this.weight = weight;
    this.targetWeight = targetWeight;
    this.exercises = [];
  }

  addExercise(exercise) {
    this.exercises.push(exercise);
  }

  updateWeight(newWeight) {
    this.weight = newWeight;
  }
}

// יצירת משתמש
const user = new User('משתמש', 50, 74, 62);

// הוספת תרגילים לדוגמה
const pushups = new Exercise('שכיבות סמיכה', 'כוח עליון');
const squats = new Exercise('סקוואטים', 'כוח תחתון');
const plank = new Exercise('פלאנק', 'ליבה');
const running = new Exercise('ריצה', 'אירובי');

user.addExercise(pushups);
user.addExercise(squats);
user.addExercise(plank);
user.addExercise(running);

// פונקציות עזר
function addWorkout(exerciseName, weight, reps) {
  const exercise = user.exercises.find(e => e.name === exerciseName);
  if (exercise) {
    exercise.addWorkout(weight, reps);
    console.log(`אימון נוסף ל${exerciseName}: ${weight} ק"ג, ${reps} חזרות`);
  } else {
    console.log(`התרגיל ${exerciseName} לא נמצא`);
  }
}

function getProgressChart(exerciseName) {
  const exercise = user.exercises.find(e => e.name === exerciseName);
  if (exercise) {
    console.log(`גרף התקדמות עבור ${exerciseName}:`);
    exercise.history.forEach(workout => {
      console.log(`${workout.date}: ${workout.weight} ק"ג, ${workout.reps} חזרות`);
    });
  } else {
    console.log(`התרגיל ${exerciseName} לא נמצא`);
  }
}

function getPersonalBests() {
  console.log('שיאים אישיים:');
  user.exercises.forEach(exercise => {
    console.log(`${exercise.name}: ${exercise.personalBest} ק"ג`);
  });
}

// דוגמה לשימוש
addWorkout('שכיבות סמיכה', 50, 10);
addWorkout('שכיבות סמיכה', 55, 8);
addWorkout('סקוואטים', 80, 12);
addWorkout('סקוואטים', 85, 10);

getProgressChart('שכיבות סמיכה');
getPersonalBests();
