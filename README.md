# Pre-assessment-task

## MATLABで作成
## 課題1

function multiplication_table()
    fprintf('   ');
    for i = 1:12
        fprintf('%4d', i);
    end
    fprintf('\n');
    
    for i = 1:12
        fprintf('%2d', i);
        for j = 1:12
            result = i * j;
            fprintf('%4d', result);
        end
        fprintf('\n');
    end
end

multiplication_table();
